pipeline {
    agent any
     tools{
         jdk 'java 17'
         maven 'maven3.9.6'
     }
    stages {
       
        stage('maven install'){
            steps{
                sh 'mvn install'
            }
        }
        stage('mvn package'){
            steps{
                sh 'mvn package'
            }
          }
        }
    }
