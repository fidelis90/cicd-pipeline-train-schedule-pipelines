pipeline {
  agent any
  stages{
    stages('build') {
      steps{
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'  
      }
      steps{
       echo 'Thank you linux academy'
      }    
    }
  }
}
