pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Cloning Repository...'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Building Project'
            }
        }

        stage('Run Script') {
            steps {
                sh './app.sh'
            }
        }

    }
}
