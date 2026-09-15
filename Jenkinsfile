pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build the application'
                echo 'Tool: Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Run unit tests'
                echo 'Run integration tests'
                echo 'Tools: JUnit and Selenium'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analyse the code and ensure it meets industry standards'
                echo 'Tool: SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Scan the code for vulnerabilities'
                echo 'Tool: OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy application to staging'
                echo 'Tool: AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Run integration tests in staging'
                echo 'Tool: Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy application to production'
                echo 'Tool: AWS EC2'
            }
        }
    }
}
