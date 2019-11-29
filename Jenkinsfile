pipeline {
    agent any
    stages {
        stage ('init') {
            steps {
                script {
                    sh 'npm i && npm run bundlesize'
                }
            }
        }
    }
}
