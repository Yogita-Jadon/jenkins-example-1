pipeline {
    agent any
    stages {
        stage('myStage'){
            steps {
                sh 'ls -la' 
            }
        }
        stage('Build') {
            steps { 
                sh 'ls' 
            }
        }
        stage('Build-new') {
            steps {
                sh 'cat Jenkinsfile'
            }
        }
        stage('Build-new') {
            steps {
                sh 'cat README.md'
            }
        }
    }
}
