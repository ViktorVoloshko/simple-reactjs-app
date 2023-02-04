pipeline {
    agent any {
        stage('Build') {
            sh 'yarn build'
        }
        stage('Deploy') {
            echo 'Starting deployment...'
        }
    }
}