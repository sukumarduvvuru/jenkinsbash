pipeline {
    agent any

    environment {
        mysonar = credentials('mysonarapplication')
    }

    stages {
        stage('test') {
            steps {
                echo 'hello test stage'
            }
        }

        stage('deploy') {
            steps {
                echo 'hello deploy'
                echo "mysonar access is: ${mysonar}"
            }
        }
    }
}
