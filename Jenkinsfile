pipeline {
    agent any 

    tools {
       maven 'mymvm'
       jdk 'javac'
    }
  
    stages {
   
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
