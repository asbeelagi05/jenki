pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git url: 'https://github.com/asbeelagi05/jenki.git',
                    branch: 'main'
            }
        }

        stage('Run Python Script') {
            steps {
                sh 'python3 python.py'
            }
        }

    }
}
