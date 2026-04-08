pipeline {
   agent any  
       stages {
           stage ('Build') {
               steps {
                   echo "Building phase"
                   sh 'pwd'
                   sh "date"
                   sh "whoami"
               }
           },
           stage ('Test') {
            steps {
                echo "Testing phase.."
                sh "ls"
                sh "pwd"
            }
           }
       }  
}
