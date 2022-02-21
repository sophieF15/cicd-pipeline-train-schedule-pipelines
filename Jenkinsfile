pipeline {
  agent any
  stages{
    stage('Build') {
      steps{
        echo "Running Build Sophie"
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'

      }
    }
  }
}
