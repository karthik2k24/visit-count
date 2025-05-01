pipeline {
    agent {
        label 'slave1'
    }
    stages {
        stage('checkout') {
            steps {
                git credentialsId: 'githubtoken', branch: 'main', url: 'https://github.com/karthik2k24/visit-count.git'
            }
        }
    }
}
