pipeline {
    agent any
    
    stages{
        stage("Building") {
            steps {
                echo "Building the code into an artifact."
            }
        }
        stage("Artifact Building"){
            steps{
                echo "Uploading artifact into the artifact repository."
            }
        }
        stage("Testing"){
            steps{
                echo "Testing the artifact."
            }
        }
        stage("Staging"){
            steps{
                echo "Staging the artifact onto the staging server."
            }
        }
        stage("Deploy"){
            steps{
                echo "Deploying the software."
            }
        }
    }
    
}
