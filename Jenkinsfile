pipeline {
    agent {
        node { label 'workstation'}
    }
    environment {
    SAMPLE_URL = "google.com"
    }

    stages {
        stage('Hai') {
            steps {
                echo 'Hello World1'
                echo "${SAMPLE_URL}"
            }
        }
    }




}