pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Webhook Committed"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
