pipeline {
    agent any
    environment{
        ENV_URL = "pipeline.learning.com"
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
          }   
        }
        stage('Stage Nmae -3') {
          steps {
                  environment {
                        ENV_URL = "stage.learning.com"
                  }
            sh '''
            echo This is 3rd Stage"
            echo this is stage env variable {$ENV_URL}
            '''
          }   
        }
    }
}