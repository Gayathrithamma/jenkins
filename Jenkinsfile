pipeline {  agent any
  stages {    stage('compile') {
      steps {        // Compile the Java file
        bat 'javac HelloWorld.java'      }
    }    stage('run') {
      steps {        // Run the compiled Java program
        bat 'java HelloWorld'      }
    }  }
}
