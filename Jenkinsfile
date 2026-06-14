pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Compiling Java program'
                sh 'rm -f Hello.class'
                sh 'javac --release 21 Hello.java'
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
