pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/your-username/my-wordpress-site.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo Building...'
                // Thêm các lệnh build cần thiết ở đây
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo Deploying...'
                // Thêm các lệnh deploy cần thiết ở đây
            }
        }
    }
}