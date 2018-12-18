pipeline {
  agent none
  
  stages {
    stage('Say Hello') {
      agent any
      steps {
        sayHello 'Awesome Student!'
      }
    }
    stage('Git Information') {
      agent any      
      steps {
        echo "My Branch Name: ${env.BRANCH_NAME}"
        }
      }
    }
}
