pipeline {
    agent any

    stages {
        stage('test') {
            steps {
                echo 'hello test stage - test'
                echo 'added webhook'
            }
        }

        stage('deploy') {
            steps {
                echo 'hello deploy'
                echo 'added webhook for building automatically'
            }
        }
    }
}
