pipeline {
agent { node { label 'docker' } }
    stages {
        stage('Build') {
            steps {
                sh '''
                apt install php
                php --version
                '''
            }
        }
    }
}
