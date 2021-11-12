@Library('Jenkins-sharedLibrary') _

pipeline{
	agent any
    stages{
	    stage('Code Scanning'){
		    steps{
		    	echo "I'm scanning the code..."
		    }
	    }
        stage('Build'){
            steps{
		build()
            }
        }
        stage('Deploy'){
            steps{
		deploy()
            }

        }
    }
}
