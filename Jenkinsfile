pipeline {
    agent {
        docker { image 'centos:7' }
    }
    stages {
        stage('Update') {
            steps {
                sh 'sudp yum -y update'
            }
        }
		stage('Install python3') {
			steps {
				sh 'sudo yum install python3'
			}
		}
    }
}
