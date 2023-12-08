pipeline {
  agent any
  stages {
    stage('dev') {
      parallel {
        stage('dev') {
          steps {
            echo 'development stage'
          }
        }

        stage('test') {
          steps {
            echo 'testing stage'
          }
        }

        stage('plugin') {
          steps {
            echo 'plugin stage'
          }
        }

      }
    }

    stage('QA') {
      steps {
        echo 'QA stage'
      }
    }

    stage('UAT') {
      steps {
        echo 'UAT Stage'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy Stage'
      }
    }

    stage('Operate') {
      steps {
        echo 'Operate Stage'
      }
    }

  }
}