pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building code using Maven to compile and package the application.'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit tests with JUnit and integration tests with TestNG.'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Analysing code quality and standards using SonarQube.'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Scanning code for vulnerabilities using OWASP Dependency-Check.'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying application to staging server (AWS EC2 instance).'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests against the staging environment.'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploying application to production server (AWS EC2 instance).'
            }
        }
    }
}