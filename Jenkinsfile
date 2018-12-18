pipeline {
  agent none
  
  stages {
    stage('Say Hello') {
        steps {
        sh 'Awesome Student!'
      }
    }
    stage('Git Information') {     
      steps {
        echo "My Branch Name: ${env.BRANCH_NAME}"
        }
      }
    }
}
