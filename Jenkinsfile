pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Webhook World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
