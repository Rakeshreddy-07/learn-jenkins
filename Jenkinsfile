pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo This is build'
            }
        }
        stage('Test') {
            steps {
                sh 'echo This is test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo This is deploy'
            }
        }
    }
    post {
        always {
            echo "this section runs always"
        }
        success{
            echo "this section runs when pipeline success"
        }
        failure{
            echo "this section runs when pipeline failure"
        }
    }
}
