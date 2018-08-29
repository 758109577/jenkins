pipeline {
    agent any 
    stages {
        stage('build') {
            steps {
                echo 'build'
                sh 'touch app03.tar'
            }
        }
        stage('test') {
            steps {
                echo "test"
            }
        }
        stage('deploy') {
            steps {
                echo "deploy"
                sh '/root/deploy.sh app03 app03.tar 192.168.1.103'
            }
        }
    }
}
