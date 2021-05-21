pipeline{
  agent any
  stages{
    stage{
      steps{
        echo "running build"
        sh './gradlew build --no-daemon'
      }
    }
  } 
} 
