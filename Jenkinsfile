pipeline {
agent { node { label 'docker' } }
    stages {
        stage('Build') {
            steps {
                sh '''
                apk add php
                ls -lah
                '''
            }
        }
    }
}
