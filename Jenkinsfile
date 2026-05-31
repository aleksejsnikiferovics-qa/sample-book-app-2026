pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo "Building sample book app"
            }
        }
    }
    stages {
        stage('deploy-dev') {
            steps {
                echo "Deploying sample book app to development environment"
            }
        }
    }
    stages {
        stage('test-dev') {
            steps {
                echo "Testing sample book app in development environment"
            }
        }
    }
    stages {
        stage('deploy-stg') {
            steps {
                echo "Deploying sample book app to staging environment"
            }
        }
    }
    stages {
        stage('test-stg') {
            steps {
                echo "Testing sample book app in staging environment"
            }
        }
    }
    stages {
        stage('deploy-prod') {
            steps {
                echo "Deploying sample book app to production environment"
            }
        }
    }
    stages {
        stage('test-prod') {
            steps {
                echo "Testing sample book app in production environment"
            }
        }
    }
}