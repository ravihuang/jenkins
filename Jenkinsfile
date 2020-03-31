pipeline {
    agent {
        docker { image 'testerq/node' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
