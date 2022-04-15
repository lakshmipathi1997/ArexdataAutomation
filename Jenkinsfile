pipeline {
    agent any
    stages { 
        stage('smokeTest') {
            steps {
                echo "Build is Started"
				bat "clean install "
				echo "Build is Successful"
            }
        }
    }
}
