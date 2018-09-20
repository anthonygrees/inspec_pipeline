pipeline {
  agent any
  stages {
    stage('Create PR') {
      steps {
        sh 'test'
      }
    }
    stage('InSpec Profile') {
      parallel {
        stage('InSpec Profile') {
          steps {
            sh 'test'
          }
        }
        stage('Inspec.yml') {
          steps {
            sh 'test'
          }
        }
        stage('Controls') {
          steps {
            sh 'test'
          }
        }
        stage('Attrbutes') {
          steps {
            sh 'test'
          }
        }
        stage('ReadMe') {
          steps {
            sh 'test'
          }
        }
        stage('Libraries') {
          steps {
            sh 'test'
          }
        }
      }
    }
    stage('Syntax Check') {
      parallel {
        stage('Syntax Check') {
          steps {
            sh 'test'
          }
        }
        stage('inspec check') {
          steps {
            sh 'test'
          }
        }
      }
    }
    stage('Lint Check') {
      parallel {
        stage('Lint Check') {
          steps {
            sh 'test'
          }
        }
        stage('Rubocop') {
          steps {
            sh 'Test'
          }
        }
      }
    }
    stage('Code Review') {
      steps {
        sh 'Test'
      }
    }
    stage('Produce Archive') {
      parallel {
        stage('Produce Archive') {
          steps {
            sh 'test'
          }
        }
        stage('Produce zip/tarball archive') {
          steps {
            sh 'test'
          }
        }
        stage('Produce a Signed Artifact') {
          steps {
            sh 'test'
          }
        }
      }
    }
    stage('Publish Archive/Lock') {
      steps {
        sh 'test'
      }
    }
    stage('Commit to Master') {
      steps {
        sh 'test'
      }
    }
  }
}