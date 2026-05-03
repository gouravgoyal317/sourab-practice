pipeline {
    agent any 

    tools {
       maven 'mymvm'
       jdk 'myjava'
    }
  
    stages {
   
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
