pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                bat ' "C:/Users/SYS-54/AppData/Local/Programs/Python/Python314/python.exe" app.py'
            }
        }
    }
}
