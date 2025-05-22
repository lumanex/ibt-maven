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
        stage('DevOps') {
            steps {
                echo 'you will make it in tech'
            }
        }
        stage('Geology') {
            steps {
                echo 'your cgpa is 2.69'
            }
        }
        stage('Git') {
            steps {
                git branch: 'main',
                    credentialsId: 'Github-credential',
                    url: 'https://github.com/lumanex/ibt-maven.git'
                sh 'ls -al'
            }
        }
    }
}
