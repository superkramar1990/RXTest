pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		whoami
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
		pwd
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}