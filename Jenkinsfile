pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
                            steps {
                              echo 'i am declarative pipline'
                                sh 'mvn --version'
                            }
                          
                       }
        stage('test'){
                   echo 'i am declarative pipline with stage 2'
                   }
         }
        }
