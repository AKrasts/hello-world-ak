pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo '--- build success ---'

                bat 'node -v'
            }
        }

        stage('Tests') {
            steps {
                echo '--- tests success ---'
            }
        }

        stage('Deploy') {
            steps {
                echo '--- deploy success ---'
            }
        }

        stage('Cleanup') {
            steps {
                echo '--- cleanup success ---'
            }
        }
    }
    
}
