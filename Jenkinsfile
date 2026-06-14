pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Compiling Java program'
                sh 'javac Hello.java'
            }
        }

        stage('Test') {
            steps {
                echo 'Checking compiled file'
                sh 'ls -l'
            }
        }

        stage('Run') {
            steps {
                echo 'Executing Java program'
                sh 'java Hello'
            }
        }
    }
}
