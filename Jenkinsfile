pipeline {
    agent {
        docker {image 'node:16-alpine'}
    }

    stages {
        stage('Verify_Docker') {
            steps {
                sh 'node --version'
            }
        }
    }
}
