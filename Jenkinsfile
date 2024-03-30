pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh "scp -r /var/jenkins_home/workspace/abc-pipline2/* root@192.168.214.145:/root/project-folder/shoes2"
            }
        }
    }
}
