pipeline{
    agent any
    stages{
        stage("Printing content"){
            steps{
                bat '''
                    cd src
                    javac App.java
                    java App
                '''
            }
        }
    }
}