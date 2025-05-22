pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hi') {
            steps {
                echo 'Hi Emma'
            }
        }
        stage('greet') {
            steps {
                echo 'you are a good boy'
            }
        }
        stage('Geology') {
            steps {
                echo 'your cgpa is 2.69'
            }
        }
        stage('Git') {
            steps {
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'Github-credential', url: 'https://github.com/lumanex/ibt-maven.git']])
                sh ls -lrt
            }
        }
    }
}
