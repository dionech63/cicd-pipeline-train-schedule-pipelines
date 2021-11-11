pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running Cheiks build auto'
        sh './gradlew build --no-deamond'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
        
     
