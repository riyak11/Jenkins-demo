

pipeline {
    agent any

    stages {
        stage('Compile Java') {
            steps {
                sh 'javac Javademo.java' 
            }
        }

        stage('Run Java') {
            steps {
                sh 'java Javademo' 
            }
        }
    }
}