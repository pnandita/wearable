@Library(['jenkins-pipeline@master']) _

pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
							  script {
							    log.info "nandita's jenkins job"
								}
                sh 'python --version'
            }
        }
    }
}
