pipeline {
  agnt any
  stages {
    satge('build') {
      steps {
        echo 'running build automation'
        sh './gradlew build -- no-daemon'
        archiveArtifacts artifacts : 'dist/trainSchedule.zip'
    }
    
    }
   
  }
}
