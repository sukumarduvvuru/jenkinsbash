pipeline {

    agent any
    stages {
        stage("build") {
            steps {
                echo "hello build stage"

            }

        }
        stage("test") {
            steps {
                echo "hello test stage"

            }

        }

        stage("deploy") {
            steps {
                echo "hello deploy stage"

            }

        }

    post{
        always {

            echo "this is post stage"
        }
    }

    }


}