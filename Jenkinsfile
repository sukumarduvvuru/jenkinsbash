pipeline {

    agent any
    stages {
        stage("build") {
            when {
                    expression {

                        BRANCH_NAME == "main"

                    }

                }
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
            
        
        }

    }


