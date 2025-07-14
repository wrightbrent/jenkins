pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git credentialsId: 'my-git-creds', url: 'https://github.com/your-username/your-repo.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building project..."'
                sh 'ls -l'
            }
        }
    }
}
