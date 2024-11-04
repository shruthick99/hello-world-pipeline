pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git 'https://your-repo-url.git' // Replace with your repo URL
            }
        }
        stage('Install Dependencies') {
            steps {
                sh 'pip install -r requirements.txt'
            }
        }
        stage('Run Application') {
            steps {
                sh 'python app.py'
            }
        }
    }
}
