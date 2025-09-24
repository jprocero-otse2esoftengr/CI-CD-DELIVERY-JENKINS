pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
               checkout scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: 'githubtoken', url: 'https://github.com/jprocero-otse2esoftengr/CI-CD-DELIVERY-JENKINS.git']])
            }
        }
    }
}