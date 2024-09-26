pipeline {
    agent any

    stages {

        stage('Build'){
            steps {
                bat 'javac Hello32.java'
            }
        }
        stage('Run'){
            steps {
                bat 'java Hello32'
            }
        }
    }
}
