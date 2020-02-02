pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the war file'
                sh 'mvn -Dmaven.test.failure.ignore=true install'
            }
        }
    }
}
