pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git credentialsId: 'my-git-creds', url: 'https://github.com/wrightbrent/jenkins.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building project..."'
                sh 'echo "forcing a build"'
                sh 'ls -l'
            }
        }
    }
}
