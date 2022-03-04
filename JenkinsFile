pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
                echo 'Building..'
                sh "mvn -Dmaven.test.failure.ignore=true clean package"
            }
        }
    }
}