pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                // Compile the Java file
                bat 'javac HelloWorld.java'
            }
        }
        
        stage('Run') {
            steps {
                // Run the compiled Java program
                bat 'java HelloWorld'
            }
        }
    }
}
