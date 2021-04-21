pipeline {
  agent any
  
  stages {
    stage('Build) {
          steps {
            echo 'Building....'
          }
    }
    stage('Test') {
          steps {
            echo 'Testing...'
          }
    }
    stage('Deploy') {
          steps {
            echo 'Deploying...'
          }
    }
    stage('Run') {
          steps {
            echo 'Running...'
            script {
              if (2+2!=4) {
                 println "buu !"
              }
              else {
                println "jeeej :)"
              }
            }
          }
    }
}
