pipeline {
    agent any
	
	triggers {
        pollSCM('*/5 * * * *')
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building release...'
				echo 'Adding more content...'
				echo 'Still more'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing release....'
				echo 'Adding more test...'
				echo 'Still more'
            }
        }
        stage('Package') {
            steps {
                echo 'Packaging release...'
				echo 'Improved packaging...'
				echo 'Still more'
            }
        }
    }
}