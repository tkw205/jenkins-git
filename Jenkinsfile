pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World again and again"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
