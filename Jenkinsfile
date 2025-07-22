pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git 'git 'https://github.com/Mouneshgouda/hi.git'
'
            }
        }
        stage('Install Dependencies') {
            steps {
                sh 'pip install -r requirements.txt'
            }
        }
        stage('Run App') {
            steps {
                sh 'python app.py'
            }
        }
    }
}
 
