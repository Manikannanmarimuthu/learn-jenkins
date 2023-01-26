pipeline {

  agent any

  stages {

    stage('Hello') {
      steps {
        echo 'Hello World'
      }
    }

    stage('Hello1') {
      steps {
        echo 'Hello World 1'
      }
    }

    stage('Hello2') {
      steps {
        echo 'Hello World 2'
      }
    }


  }

  post {
    always {
      echo "sending email Jekins Test"
    }
  }

}