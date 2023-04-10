// pipeline {
//     agent { label 'ws'}
//     environment{
//         ENV_URL = "pipeline.learning.com"
//         SSH_CREDENTIALS = credentials('SSH_CRED')
//     }
//     // triggers { pollSCM('*/1 * * * *') }
//     // parameters {
//     //     string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')

//     //     text(name: 'BIOGRAPHY', defaultValue: '', description: 'Enter some information about the person')

//     //     booleanParam(name: 'TOGGLE', defaultValue: true, description: 'Toggle this value')

//     //     choice(name: 'CHOICE', choices: ['One', 'Two', 'Three'], description: 'Pick something')

//     //     password(name: 'PASSWORD', defaultValue: 'SECRET', description: 'Enter a password')
//     // }
//     stages{
//         stage('Stage Name -1') {
//           steps {
//             sh "cat /home/centos/file.txt"
//             sh "echo this is my first stage in the jenkins pipleline"
//           }   
//         }
//         stage('Stage Nmae -2') {
//           steps {
//             sh "echo Printing the envt varibale $ENV_URL"
//             sh "env"
//           }   
//         }
//         stage('Stage Nmae -3') {
//                environment {
//                         ENV_URL = "stage.learning.com"
//                   }
//           steps {
//             sh "echo This is 3rd Stage and this is stage env variable {$ENV_URL}"
//           }   
//         }
//     }
// }



node {
    stage('Test'){
      print 'Welcome to the scripted pipeline'
    }

    stage('QA'){
      print 'Scripted pipeline to make things easy'
    }
}