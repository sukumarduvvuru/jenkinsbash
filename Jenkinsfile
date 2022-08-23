pipeline {
    agent any

    stages {
        stage('test') {
            environment {
                sonar = credentials('mysonarid')
            }
            steps {
                echo 'hello test stage'
                echo "my sonar access key is: ${sonar}"
                echo 'added webhook'
            }
        }

        stage('deploy') {
            steps {
                echo 'hello deploy'
                echo "added webhook"
            }
        }
    }
}
