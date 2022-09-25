pipeline {
  agent any
  tools {
    NodeJS 'Node-16.15'
  }
  stages {
    stage("build") {
      steps {
        echo "Building the app"
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
