pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/yourusername/reponame.git'
            }
        }

        stage('Run Script') {
            steps {
                sh 'chmod +x script.sh'
                sh './script.sh'
            }
        }

    }
}
