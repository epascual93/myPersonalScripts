pipeline {
    agent { docker { image 'dotnet:2.1-sdk' } }
    stages {
        stage('build') {
            steps {
                sh 'dotnet --version'
            }
        }
    }
}
