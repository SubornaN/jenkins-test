pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO WORLD"'
      sh '''
        echo "Welcome to B2"
        uname -a
        '''
      }
    }
    stage ('Test') {
       steps {
       sh 'echo "HELLO TEST"'
       sh '''
         echo "This list current dir"
         pwd
         '''
       }
     }
  }
}
