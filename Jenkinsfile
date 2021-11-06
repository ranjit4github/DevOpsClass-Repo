pipeline{
	agent any
    stages{
        stage('Build'){
            steps{
		echo "This the Build stage"
            }
        }
        stage('Test'){
            steps{
		echo "This is the Testing stage"
            }
            steps{
		echo "I'm extra step"
            }

        }
        stage('Delivery'){
            steps{
                echo "Waiting for delivery....."
            }
        }
    }
}
