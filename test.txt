

pipeline {
    agent any

    stages {
        stage('scm checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Abdelaty28/docker.git'
            }
        }
         stage('build') {
            steps {
                echo 'build step'
            }
        }
         stage('test') {
            steps {
                echo 'test step'
            }
        }
         stage('deploy') {
            steps {
                echo 'deploy step'
            }
        }
    }
}
