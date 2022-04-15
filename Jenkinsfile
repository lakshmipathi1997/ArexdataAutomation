pipeline {
    agent any
    stages { 
        stage('CleanUP') {
            steps {
                echo "Build is Started"
				bat "mvn clean "
				echo "Build is Successful"
            }
		stage('Smoke Test'){
			steps{
				echo "Executing Smoke Test Cases"
			}
		}
        }
    }
}
