pipeline {
    agent {
        docker { image 'centos:7' }
    }
    stages {
        stage('Update) {
            steps {
                sh 'yum -y update'
            }
        }
		stage('Install python3') {
			steps {
				sh 'yum install python3'
			}
		}
    }
}
