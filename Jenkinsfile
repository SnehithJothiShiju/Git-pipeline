pipeline {
  agent any
  stages {
    stage('Build') { // This stage is for building the application
      steps { echo 'Using Gradle to build the application' }
    }
    stage('Unit and Integration Tests') { // This stage is for running unit and integration tests
      steps { echo 'Using Python to run tests' }
    }
    stage('Code Analysis') {
      steps { echo 'Using SonarQube for code quality checks' }
    }
    stage('Security Scan') {
      steps { echo 'Using OWASP to scan for vulnerabilities' }
    }
    stage('Deploy to Staging') {
      steps { echo 'Deploying using Docker + Kubernetes (staging)' }
    }
    stage('Integration Tests on Staging') {
      steps { echo 'Running Karate DSL on staging' }
    }
    stage('Deploy to Production') {
      steps { echo 'Deploying using Terraform + AWS CodeDeploy to production' }
    }
  }
}
