pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/23p61a0540-glitch/devops3.git'
            }
        }

        stage('Build') {
            steps {
                sh 'javac Hello.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Hello'
            }
        }
    }
}
