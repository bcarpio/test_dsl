@Library('Utilities')
import asu.selfservice.Utilities
def u = new Utilities()

pipeline {
  agent any
  stages {
    stage('Dev: HelloWorld') {
      steps {
         script{
           u.helloworld('Brian is Amazing')
         }
      }
    }
  }
}
