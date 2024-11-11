pipeline {
    agent any

    stages {
        stage('Build') {
           
            steps {
                bar '''
                    ls -la
                    npm --version
                    node --version
                    npm ci
                    npm run build
                    ls -la
                '''
            }
        }
    }
}
