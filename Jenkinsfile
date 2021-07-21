pipeline {
    agent any
    tools {
        go 'MyGo'
    }
    stages {
        stage('build') {
            steps {
                sh 'go mod init hello'
                sh 'go build'
                sh './hello'
                sh 'rm hello'
            }
        }
    }
}
