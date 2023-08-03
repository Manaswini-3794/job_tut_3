pipeline {
  agent {
     node { 
        label 'lsv03259'
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
