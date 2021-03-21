pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'running build automation'
        bat './gradlew build -- no-daemon'
        archiveArtifacts artifacts : 'dist/trainSchedule.zip'
      }
    }
  }
}
