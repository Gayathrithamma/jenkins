pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                // Compile the Java file
                sh 'javac HelloWorld.java'
            }
        }
        
        stage('Run') {
            steps {
                // Run the compiled Java program
                sh 'java HelloWorld'
            }
        }
    }
}
