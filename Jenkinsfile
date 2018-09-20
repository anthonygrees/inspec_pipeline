pipeline {
  agent any
  stages {
    stage('Create PR') {
      steps {
        echo 'Create PR'
      }
    }
    stage('InSpec Profile') {
      parallel {
        stage('InSpec Profile') {
          steps {
            echo 'InSpec Profile'
          }
        }
        stage('Inspec.yml') {
          steps {
            echo 'Test'
          }
        }
        stage('Controls') {
          steps {
            echo 'test'
          }
        }
        stage('Attrbutes') {
          steps {
            echo 'test'
          }
        }
        stage('ReadMe') {
          steps {
            echo 'test'
          }
        }
        stage('Libraries') {
          steps {
            echo 'test'
          }
        }
      }
    }
    stage('Syntax Check') {
      parallel {
        stage('Syntax Check') {
          steps {
            echo 'test'
          }
        }
        stage('inspec check') {
          steps {
            echo 'test'
          }
        }
      }
    }
    stage('Lint Check') {
      parallel {
        stage('Lint Check') {
          steps {
            echo 'test'
          }
        }
        stage('Rubocop') {
          steps {
            echo 'Test'
          }
        }
      }
    }
    stage('Code Review') {
      steps {
        echo 'Test'
      }
    }
    stage('Produce Archive') {
      parallel {
        stage('Produce Archive') {
          steps {
            echo 'test'
          }
        }
        stage('Produce zip/tarball archive') {
          steps {
            echo 'test'
          }
        }
        stage('Produce a Signed Artifact') {
          steps {
            echo 'test'
          }
        }
      }
    }
    stage('Publish Archive/Lock') {
      steps {
        echo 'test'
      }
    }
    stage('Commit to Master') {
      steps {
        echo 'test'
      }
    }
  }
}
