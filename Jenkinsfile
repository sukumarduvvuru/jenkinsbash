pipeline {
    agent any

    stages {
        stage('testing') {
            steps {
                echo 'hello test stage - test'
                echo 'added webhook in configure section'
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
