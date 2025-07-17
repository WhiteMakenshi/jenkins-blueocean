pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        echo 'Compiling'
        sh 'date'
      }
    }

    stage('Testing') {
      steps {
        echo 'I am in Testing'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

    stage('Notify') {
      steps {
        echo 'Notify the deploy'
      }
    }

  }
}