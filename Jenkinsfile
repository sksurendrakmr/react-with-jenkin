pipeline {
  agent any
  tools {
    nodejs "Node-16.15"
  }
  stages {
    stage("build") {
      steps {
        echo "Building the app"
        sh "npm install"
      }  
    }
    stage("test") {
      steps {
        echo "testing the app"
      }  
    }
    stage("deploy") {
      steps {
        echo "Deploying the app"
      }  
    }
  }
}
