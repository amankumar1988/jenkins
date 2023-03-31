pipeline {
    agent any
    environment{
        ENV_URL = "pipeline.learning.com"
        SSH_CREDENTIALS = credentials('SSH_CRED')
    }
    stages{
        stage('Stage Name -1') {
          steps {
            sh "echo this is my first stage in the jenkins pipleline"
          }   
        }
        stage('Stage Nmae -2') {
          steps {
            sh "echo Printing the envt varibale $ENV_URL"
            sh "env"
          }   
        }
        stage('Stage Nmae -3') {
               environment {
                        ENV_URL = "stage.learning.com"
                  }
          steps {
            sh "echo This is 3rd Stage and this is stage env variable {$ENV_URL}"
          }   
        }
    }
}