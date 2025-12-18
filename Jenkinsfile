pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/ashutoshmishra789/jenkins-github-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build triggered from GitHub webhook'
                sh 'ls -la'
            }
        }
    }
}
