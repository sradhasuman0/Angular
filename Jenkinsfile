properties([pipelineTriggers([githubPush()])])
pipeline{
    agent any
    stages {
    stage('Install') {
      steps { sh 'npm install' }
    } 
  }
}
