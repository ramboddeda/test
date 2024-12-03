pipeline {
    agent none
    stages {
        stage ('SKIP stage testing') {
            steps{
                agent any
            options {
                skipDefaultCheckout()
            }
            echo "Trying skip default checkout"
            }
        }
    }
}
