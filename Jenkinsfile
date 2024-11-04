pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/shruthick99/hello-world.' // 
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
