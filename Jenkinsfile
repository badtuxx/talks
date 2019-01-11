pipeline {
    agent any

    stages {
        stage("pre-checks") {
            steps {
                echo 'pre-checks'
            }
        }
        stage("Testing - UT IT") {
            steps {
                echo 'Testing..'
            }

        }
        stage("Build") {
            steps {
                sh "/bin/cat LICENSE"
            }
        
        }
    }
}

