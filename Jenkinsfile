pipeline {
  agent any
  stages {
    stage('Plan') {
      steps {
        echo 'I have a plan to work on CICD'
      }
    }

    stage('Code') {
      steps {
        echo 'I have a code to work on CICD'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'I have a build to work on CICD'
          }
        }

        stage('Test') {
          steps {
            echo 'I have a test to work on CICD'
          }
        }

        stage('Release') {
          steps {
            echo 'I have a release to work on CICD'
          }
        }

        stage('Deploy') {
          steps {
            echo 'I have a deploy to work on CICD'
          }
        }

        stage('Operate') {
          steps {
            echo 'I have a operate to work on CICD'
          }
        }

      }
    }

  }
}