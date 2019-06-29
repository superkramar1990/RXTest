pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		echo 'Zalypka'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
		touch zalypa.txt
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}