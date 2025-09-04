pipeline {
  agent {
    docker {
      image 'moodlehq/moodle-php-apache'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'htop install'
      }
    }

  }
}