pipeline {
    agent any

    stages {
        stage('Build') {
           
            steps {
                bat '''
                    dir
                    npm --version
                    node --version
                    npm ci
                    npm run build
                    dir
                '''
            }
        }
    }
}
