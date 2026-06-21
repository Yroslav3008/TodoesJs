pipeline{
  agent any
  stages{
    stage('Checkout code'){
      steps{
        git "https://github.com/Yroslav3008/TodoesJs/"
      }
    }
    stage('Build'){
      steps{
        sh 'echo "Building the app"'
      }
    }
    stage('Test'){
      steps{
        sh 'echo "Running comand"'
      }
    }
    stage('Deploying'){
      steps{
        sh 'echo "deploying"'
      }
    }
  }
}
