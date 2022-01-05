pipeline {
  agent any
  stages {
    stage ('build')
      steps{
        echo 'running automiation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artfifats:'dist/trainSchedule.zip'
        
    }
  }
}
