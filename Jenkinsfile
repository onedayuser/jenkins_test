pipeline {
    agent { docker 'circleci/node:9.3-stretch-browsers' }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
