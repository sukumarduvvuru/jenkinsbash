pipeline {
    agent any

    stages {
        stage('test') {
            steps {
                echo 'hello test stage - dev branch change'
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
