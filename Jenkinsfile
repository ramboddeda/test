//Trying commenting skipdefalut check
pipeline {
    agent none
    stages {
        stage ('SKIP stage testing') {
            agent any
            /* options {
                skipDefaultCheckout()
            } */
            steps{
            echo "Trying skip default checkout"
            }
        }
    }
}
