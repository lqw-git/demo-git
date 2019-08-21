pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                checkout scm
				bat 'build.bat'
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
