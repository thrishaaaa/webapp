pipeline {
    agent any

    tools {
        maven 'Maven'
        jdk 'JDK'
    }

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/thrishaaaa/webapp.git'

            }
        }

        stage('Build WAR') {
            steps {
                sh 'mvn clean package'
            }
        }

        

        }
    }
