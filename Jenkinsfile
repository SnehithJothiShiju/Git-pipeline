pipeline {
  agent any
  stages {
    stage('Build') { // This stage is for building the application
      steps { echo 'Using Gradle to build the application' }
    }
    stage('Unit and Integration Tests') { // This stage is for running unit and integration tests
      steps { echo 'Using Python to run tests' }
    }
    stage('Code Analysis') { // This stage is for code quality checks
      steps { echo 'Using SonarQube for code quality checks' }
    }
    stage('Security Scan') { // This stage is for scanning the application for vulnerabilities
      steps { echo 'Using OWASP to scan for vulnerabilities' }
    }
    stage('Deploy to Staging') { // This stage is for deploying the application to a staging environment
      steps { echo 'Deploying using Docker + Kubernetes (staging)' }
    }
    stage('Integration Tests on Staging') { // This stage is for running integration tests on the staging environment
      steps { echo 'Running Karate DSL on staging' }
    }
    stage('Deploy to Production') { // This stage is for deploying the application to a production environment
      steps { echo 'Deploying using Terraform + AWS CodeDeploy to production' }
    }
  }
}
// This Jenkinsfile defines a CI/CD pipeline with multiple stages: