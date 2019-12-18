pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World from github"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
