pipeline {
    agent any

    stages {
        stage('confirm version') {
            steps {
                nodejs('NodeJs18.3.0') {
                    sh 'node -v'
                    sh 'npm -v'
                    echo "Hello Kaew"
                }
            }
        }
        stage('install node packages') {
            steps {
                nodejs('NodeJs18.3.0') {
                    sh 'npm install'
                }
            }
        }
    }
}
