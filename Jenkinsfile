pipeline {
agent { node { label 'docker' } }
    stages {
        stage('Build') {
            steps {
                sh '''
                sudo apt install php
                php --version
                '''
            }
        }
    }
}
