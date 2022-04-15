pipeline {
    agent any
    stages { 
        stage('CleanUP') {
            steps {
                echo "Build is Started"
				bat "mvn clean "
				echo "Build is Successful"
            }
        }
    }
}
