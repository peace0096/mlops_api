pipeline {
    agent any
    stages {
        stage("build") {
                steps {
                    echo "building the application..."
                }
            }
        stage("test") {
            steps {
                echo "testing the application..."
            }
        }
        stage("deploy") {
            steps {
                echo "${env.GIT_BRANCH}"
                echo "deploying the application..."
            }
        }
    }
    

}