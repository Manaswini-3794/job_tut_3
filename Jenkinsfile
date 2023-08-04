pipeline {
  agent {
     node { 
        label 'manaswini-lp'
        } 
  }
    stages{
    stage('build') {
      steps {
        sh ''' javac hello.java
                java hello
              echo 'this is the code to find gcd'
        '''
      }
    }
    }
}
