pipeline {
    agent any
    triggers { 
        pollSCM('H/2 * * * *') 
    }
    stages {
        stage('Example1') {
            steps {
                echo 'Hello World1'
            }
        }
        stage('Example2') {
            steps {
                echo 'Hello World2!!!'
            }
        }
    }
}
