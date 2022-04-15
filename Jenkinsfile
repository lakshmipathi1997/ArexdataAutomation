pipeline {
    agent any
    stages { 
        stage('CleanUP') {
            steps {
                echo "Build is Started"
				sh "mvn clean "
				echo "Build is Successful"
            }
        }
    }
}
