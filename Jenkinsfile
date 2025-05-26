pipeline {
    agent any
    stages {
        stage('Compile Java') {
            steps {
                sh 'javac Main.java'
            }
        }
        stage('Run Java') {
            steps {
                sh 'java Main'
            }
        }
    }
}
