pipeline {
    agent any
    stages {
        stage('Installing prereqs') {
            steps {
                echo 'Installing flask..'
                sh("pip install flask")
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
            }
        }
    }
}
