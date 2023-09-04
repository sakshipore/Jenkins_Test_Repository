pipeline {
    agent any

    stages {
        stage('Compile and Run') {
            steps {
                bat 'cd src'
                bat 'javac App.java'
                bat 'java App'
            }
        }
    }
}
