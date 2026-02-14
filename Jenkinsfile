pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Riya0007/Hello-World.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Building project'
            }
        }
    }
}
