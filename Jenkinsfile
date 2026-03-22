pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'Building project...'
      }
    }
    
    stage('Docker Build') {
      steps {
        sh 'sudo docker build -t devops-lab .'
      }
    }
    
    stage('Deploy') {
      steps {
        echo 'Deploying project...'
      }
    }
  }
}
