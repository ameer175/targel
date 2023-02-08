pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/ameer175/targel.git'
                bat 'dir'
                bat 'python mainn.py'
            }
        }
    }
}
