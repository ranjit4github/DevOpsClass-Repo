pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "Hello Jenkins.. Building in progress..."
            }
        }
        stage('Test') { 
            steps {
                echo "Hello Jenkins.. Testing in progress..." 
              script {
                echo "This is the scripted bracket..."
              }
            }
        }
        stage('Deploy') { 
            steps {
                echo "Hello Jenkins.. Deployment in progress..."
            }
        }
    }
}
