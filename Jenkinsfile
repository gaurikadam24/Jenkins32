pipeline {
    agent any

    stages {

        stage('Build'){
            steps {
                bat 'javac hello32.java'
            }
        }
        stage('Run'){
            steps {
                bat 'java hello32'
            }
        }
    }
}
