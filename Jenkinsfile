@Library('jenkins-pipeline@master')

pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
							  log.info "nandita's jenkins job"
                sh 'python --version'
            }
        }
    }
}
