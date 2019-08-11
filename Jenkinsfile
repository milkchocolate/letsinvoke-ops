pipeline {
    agent any
    stages {
        stage('Deploy to Production') {
        agent { docker 'aaronyunan/jdk8-awscli' }
            steps {
                sh './auto/deploy'
            }
        }
    }
}
