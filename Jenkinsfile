pipeline {
    agent any

    triggers {
        pollSCM('H/5 * * * *')
    }

    stages {
        stage('1. Checkout Code') {
            steps {
                echo 'Task: Fetch the latest code from GitHub repository'
                echo 'Tool: Git'
            }
        }

        stage('2. Build') {
            steps {
                echo 'Task: Compile or prepare the application'
                echo 'Tool: Maven'
            }
        }

        stage('3. Unit Testing') {
            steps {
                echo 'Task: Run unit tests'
                echo 'Tool: JUnit'
            }
        }

        stage('4. Code Quality Check') {
            steps {
                echo 'Task: Check code quality and bugs'
                echo 'Tool: SonarQube'
            }
        }

        stage('5. Security Scan') {
            steps {
                echo 'Task: Scan for vulnerabilities'
                echo 'Tool: Snyk'
            }
        }

        stage('6. Package Application') {
            steps {
                echo 'Task: Package application'
                echo 'Tool: Docker'
            }
        }

        stage('7. Mock Deployment') {
            steps {
                echo 'Task: Simulate deployment'
                echo 'Tool: Jenkins'
            }
        }
    }
}