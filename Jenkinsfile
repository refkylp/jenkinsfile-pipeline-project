pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code 3'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code 2.'
                sh 'java Hello'
            }
        }
    }
}