pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Guru..."'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
