pipeline {
  agent any
  stages {
    stage('plan') {
      steps {
        echo 'i have a plan to work on cicd'
      }
    }

    stage('code') {
      steps {
        echo 'i have a code to work on cicd'
      }
    }

    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'i have a build to work on cicd'
          }
        }

        stage('test') {
          steps {
            echo 'i have a test to work on cicd'
          }
        }

        stage('release') {
          steps {
            echo 'i have a release to work on cicd'
          }
        }

        stage('deploy') {
          steps {
            echo 'i have a deply to work on cicd'
          }
        }

      }
    }

  }
}