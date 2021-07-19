pipeline {
agent { node { label 'docker' } }
    stages {
        stage('Build') {
            steps {
                script('''
                   apt install php
                   php --version
                ''')
            }
        }
    }
}
