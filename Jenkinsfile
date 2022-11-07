pipeline {
  agent any
  stages {
    stage ('Stage Build') {
      steps {
        echo 'Running Build AUtomation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }        
  }     
}        
            
        
    
