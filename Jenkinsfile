pipeline {
    agent {
        docker { 
			image 'centos:7' 
			args '-u root'
		}
    }
    stages {
        stage('Configure build environment') {
            steps {
                sh 'yum -y update'
				sh 'yum -y install epel-release'
				sh 'yum -y install python34'
			}
		}
    }
}
