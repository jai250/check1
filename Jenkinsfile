pipeline {
    agent any
    stages {
        stage('build') {
            steps{
                sh 'sleep 4; echo "build done"'
            }
        }
        stage('test') {
            steps{
                sh 'sleep 6; echo "test done"'
            }
        }
        stage('deploy') {
            steps{
            sh 'sleep 7; echo "deploy done"'
            }
        }
        }
}
