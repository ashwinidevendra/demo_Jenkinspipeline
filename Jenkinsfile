pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
         stage('test'){
                 steps{
                       echo 'i am declarative pipline with stage  1'
                     }
                     }
        stage('build') {
                            steps {
                              echo 'i am declarative pipline'
                            }  
                        }
         }
        }
