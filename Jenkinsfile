pipeline {
  agent any

  stages {
    stage('Stage 1 - Build') {
      steps {
        echo 'Stage 1 - Build'
        echo 'Task: Build the code using a build automation tool to compile and package the code.'
        echo 'Tool: Maven.'
      }
    }

    stage('Stage 2 - Unit and Integration Tests') {
      steps {
        echo 'Stage 2 - Unit and Integration Tests'
        echo 'Task: Run unit tests to ensure the code functions as expected and run integration tests to ensure the different components of the application work together as expected.'
        echo 'Tool: JUnit.'
      }
    }

    stage('Stage 3 - Code Analysis') {
      steps {
        echo 'Stage 3 - Code Analysis'
        echo 'Task: Integrate a code analysis tool to analyse the code and ensure it meets industry standards.'
        echo 'Tool: SonarQube.'
      }
    }

    stage('Stage 4 - Security Scan') {
      steps {
        echo 'Stage 4 - Security Scan'
        echo 'Task: Perform a security scan on the code using a tool to identify any vulnerabilities.'
        echo 'Tool: Snyk.'
      }
    }

    stage('Stage 5 - Deploy to Staging') {
      steps {
        echo 'Stage 5 - Deploy to Staging'
        echo 'Task: Deploy the application to a staging server (production-like environment).'
        echo 'Tool: AWS EC2 (with Docker).'
      }
    }

    stage('Stage 6 - Integration Tests on Staging') {
      steps {
        echo 'Stage 6 - Integration Tests on Staging'
        echo 'Task: Run integration tests on the staging environment to ensure the application functions as expected in a production-like environment.'
        echo 'Tool: Postman + Newman.'
      }
    }

    stage('Stage 7 - Deploy to Production') {
      steps {
        echo 'Stage 7 — Deploy to Production'
        echo 'Task: Deploy the application to a production server.'
        echo 'Tool: AWS CodeDeploy.'
      }
    }

    stage('Stage 8 - Testing Trigger') {
      steps {
        echo 'This stage is added only to test auto-trigger from GitHub commit.'
      }
    }

  }
}
