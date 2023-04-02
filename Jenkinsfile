pipeline {
    agent {
        docker {
            image 'node:16-buster-slim' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
<<<<<<< HEAD
    stage('Test') { 
      steps {
        sh './jenkins/scripts/test.sh' 
      }
    }
  }
}
=======
}
>>>>>>> d96b1ee0ad2dac2bf0eef74246b6a266dcb2154d
