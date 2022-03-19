pipeline {
    agent any

    stages {
        stage('Testing') {
            steps {
                echo 'Runing test'
				bat 'mvn test'
            }
        }
        stage('Test') {
            steps {
                echo 'Runing build'
				bat 'mvn package'
            }
        }
    }
}
