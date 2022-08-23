pipeline {
    agent any

    environment {
        mysonarcred = credentials('mysonarapplication')
    }

    stages {
        stage('build') {
            steps {
                echo 'hello world build stage'
                sh "my sonar cred is: ${mysonarcred}"
            }
        }

        stage('test') {
            steps {
                echo 'hello test stage'
            }
        }

        stage('deploy') {
            steps {
                echo 'hello deploy'
            }
        }
    }
}
