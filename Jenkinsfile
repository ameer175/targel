pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'dir'
                bat 'python mainn.py'
                bat 'python p.py'
            }
        }
    }
}
