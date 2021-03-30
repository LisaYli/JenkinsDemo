pipeline {
    agent any
    tools{
        maven 'Maven3.6.3'

    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'java --version'
                sh 'mvn clean compile'

            }
        }
    }
}