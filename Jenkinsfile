pipeline {

    agent any
    stages {
        stage("build") {
            steps {
                echo "hello build stage"

                when {
                    expression {

                        BUILD_NAME == "main"
                        echo "this is main branch"

                    }

                }
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
            
        
        }

    }


