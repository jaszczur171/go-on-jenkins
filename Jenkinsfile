pipeline {
    agent any
    tools {
        go 'go-latest'
    }
    environment {
        GO111MODEULT = 'on'
    }
    stages {
        stage('Build') {
            steps {
                sh 'go build'
            }
        }
    }
}