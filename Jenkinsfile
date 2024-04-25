pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh "scp -r /var/jenkins_home/workspace/1st-pipline-with-jenkinsfile/* root@164.92.100.171:/project-foler/shoes"
            }
        }
    }
}
