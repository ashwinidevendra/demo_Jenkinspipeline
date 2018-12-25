pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
                    steps {
                      echo 'i am declarative pipline'
                        sh 'mvn --version'
                    }
                    steps {
                      echo 'i am declarative pipline with step 2'
                        sh 'mvn --version'
                    }
        }
        agent any
        stage('test'){
                   echo 'i am declarative pipline with stage 2'
        }
    }
}
