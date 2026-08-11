pipeline {
    agent {
        label 'linux-agent'
    }

    stages {

        stage('Test Agent') {
            steps {
                sh 'hostname'
                sh 'whoami'
                sh 'java -version'
            }
        }

        stage('Build') {
            steps {
                echo 'Build is running on Jenkins Agent'
            }
        }
    }
}
