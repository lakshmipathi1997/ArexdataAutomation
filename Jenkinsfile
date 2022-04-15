pipeline {
    agent any
    stages { 
        stage('smokeTest') {
            steps {
                echo "Build is Started"
				bat "mvn test "
				echo "Build is Successful"
            }
        }
    }
}
