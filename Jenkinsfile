pipeline {
    agent any
    stages { 
        stage('smokeTest') {
            steps {
                echo "Build is Started"
				bat "mvn clean install "
				echo "Build is Successful"
            }
        }
    }
}
