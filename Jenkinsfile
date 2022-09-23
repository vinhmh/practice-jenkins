pipeline {
    agent any
    options {
        timeout(time: 1, unit: 'HOURS') 
    }

    stages {

        stage('Build') {
            steps {
                sh "echo hello cicd"
                sh "echo '${env.GIT_BRANCH}'"
                }
            }
        }
    }
