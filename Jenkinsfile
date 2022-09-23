pipeline {
    agent any
    options {
        timeout(time: 1, unit: 'HOURS') 
    }

    stages {

        stage('Build') {
            steps {
                sh "echo hello main branch update"
                sh "echo '${env.GIT_BRANCH}'"
                }
            }
        }
    }
