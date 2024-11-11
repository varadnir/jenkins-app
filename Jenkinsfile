pipeline {
    agent any

    stages {
        stage('Build') {
           
            steps {
                bar '''
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
