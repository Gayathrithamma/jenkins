pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Assuming the Java file is in source control
                checkout scm
            }
        }

        stage('Compile') {
            steps {
                // Compile HelloWorld.java
                sh 'javac HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                // Run the compiled HelloWorld class
                sh 'java HelloWorld'
            }
        }
    }
}
