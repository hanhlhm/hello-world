pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'javac hello.java'
            }
        }
        stage('run') {
            steps {
                sh 'java hello'
            }
        }
    }
}
