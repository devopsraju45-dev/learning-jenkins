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
                echo 'Hello World'
                echo "${SAMPLE_URL}"
            }
        }
    }




}