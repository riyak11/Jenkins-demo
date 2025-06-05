

pipeline {
    agent any

    stages {
        stage('Compile Java') {
            steps {
                bat 'javac Javademo.java' 
            }
        }

        stage('Run Java') {
            steps {
                bat 'java Javademo' 
            }
        }
    }
}