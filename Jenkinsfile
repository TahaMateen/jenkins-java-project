pipeline {
  agent any
  
  stages {
    stage('Say Hello') {
        steps {
        echo 'Awesome Student!'
      }
    }
    stage('Git Information') {     
      steps {
        echo "My Branch Name: ${env.BRANCH_NAME}"
        }
      }
    }
}
