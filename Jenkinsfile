pipeline {

    agent any
    environment {

        VERSIONNUMBER = "1.0"
    }
    stages {
        stage("build") {
            when {
                    expression {

                        BRANCH_NAME == "main"

                    }

                }
            steps {
                echo "hello build stage - with version  ${VERSIONNUMBER}"

                
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


