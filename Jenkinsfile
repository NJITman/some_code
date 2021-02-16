pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        echo 'hello from the trigger periodic'
      }
    }

  }
  triggers {
    cron('H/15 * * * *')
  }
}
