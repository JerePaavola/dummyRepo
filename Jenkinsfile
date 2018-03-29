pipeline {
    agent any
	
	triggers {
        cron('3 * * * *')
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building branch 2...'
				echo 'Adding more content...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing branch 2...'
				echo 'Adding more test...'
            }
        }
        stage('Package') {
            steps {
                echo 'Packaging branch 2...'
				echo 'Improved pacakaging...'
            }
        }
    }
}