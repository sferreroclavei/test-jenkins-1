pipeline {
 agent any
 stages {
  stage ('Checkout-git'){
          steps{
            git pull: true, url: 'git@github.com:sferreroclavei/test-jenkins-1.git'
            }
   
   }
   
   stage('TestApp0){
          steps{
            sh '''
              bash ./scripts/hola.sh
            '''
            }
     }
}
