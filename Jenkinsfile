pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Compile and Run') {
            steps {
                bat 'javac App.java'
                bat 'java App'
            }
        }
    }
}
