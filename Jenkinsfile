pipeline {
    agent any

    stages {
        stage('CLONING REPO') {
            steps {
                git branch: 'main', url: 'https://github.com/KGUPTA22/testing_git.git'
                sh 'python3 app.py'
            }
        }
    }
}
