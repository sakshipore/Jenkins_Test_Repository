pipeline{
    agent any
    stages{
        stage("Printing content"){
            steps{
                sh "pwd"
                sh "cd src"
                sh "javac App.java"
                sh "java App"
            }
        }
    }
}