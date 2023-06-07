pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Hello build'
                sleep 10
            }
        }
         stage('test') {
            steps {
                echo 'Hello test'
                sleep 10
            }
             stage('deploy') {
            steps {
                echo 'Hello deploy'
                sleep 10
            }
             stage('docker') {
            steps {
                echo 'Hello docker'
            }
        }
    }
}
