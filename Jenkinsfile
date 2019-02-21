pipeline {
    agent { docker { image 'node:11.1' } }
    stages {
        stage('build') {
            steps {
                sh 'npm start'
            }
        }
    }
}
