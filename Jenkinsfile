pipeline {
    agent any

    stages {
        stage('dev') {
            steps {
                echo 'Hello World'
                build 'dev_job'
            }
        }       
        stage('build') {
            steps {
                echo 'Hello World'
                build 'buld_job'
            }
        }
    }
}
