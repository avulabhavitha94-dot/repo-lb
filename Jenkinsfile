pipeline {
    agent any

    stages {
        stage('install maven') {
            steps {
                sh 'sudo dnf install maven -y'
            }
        }
    stage('clean package') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
