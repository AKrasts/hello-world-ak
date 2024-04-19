pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo '--- build success ---'

                sh 'node -v'
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
