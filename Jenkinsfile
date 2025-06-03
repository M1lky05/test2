pipeline {
    agent any

    stages {
        stage("Build") {
            steps {
                echo 'Using Maven to compile and package the code into a deployable format'
            }
        }

        stage("Unit and integration tests") {
            steps {
                echo 'Using JUnit and Postman to run unit and integration tests to verify individual components and how they work together'
            }
        }

        stage("Code analysis") {
            steps {
                echo 'Using SonarQube to analyse code quality, identify bugs and ensure code meets industry standards'
            }
        }

        stage("Security scan") {
            steps {
                echo 'Using OWASP Dependency Check to scan for known security vulnerabilities in dependencies'
            }
        }

        stage("Deploy to staging") {
            steps {
                echo 'Using AWS CLI to deploy the application to a staging environment on EC2 instance'
            }
        }

        stage("Integration tests on staging") {
            steps {
                echo 'Using Selenium to perform integration tests in a production-like staging environment'
            }
        }

        stage("Deploy to production") {
            steps {
                echo 'Using Ansible to deploy the final version of the application to the production server'
            }
        }
    }
}

