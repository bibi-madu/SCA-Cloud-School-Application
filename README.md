# SCA-Cloud-School-Application
pipeline {
    agent any
    
 stages {
    stage('Build') {
      steps{
        echo 'Building..'
       }
      }
     stage('Deploy') {
      steps {
        echo 'Deploying..'
        }
       }
      }
