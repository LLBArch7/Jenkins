pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO Lora Lee"'
      sh '''
        echo "Welcome to B2"
        uname -a
        '''
      }
    }
    stage ('Test') {
      steps {
      sh 'echo "HELLO Lora"'
      sh '''
        echo "This is just a test"
        pwd
        '''
      }
    }
  }
}
