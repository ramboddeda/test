pipeline {
    agent none
    stages {
        stage ('SKIP stage testing') {
            agent any
            options {
                skipDefaultCheckout()
            }
            echo "Trying skip default checkout"
        }
    }
}
