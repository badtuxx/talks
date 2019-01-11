pipeline {
    agent any

    stages {
        stage("Cloning repo") {
            steps {
                checkout scm
            }
        }
        stage("Testing - UT IT") {
            steps {
                echo 'Testing..'
            }

        }
        stage("Build") {
            steps {
                sh "/bin/cat ./talks/LICENSE"
            }
        
        }
    }
}

