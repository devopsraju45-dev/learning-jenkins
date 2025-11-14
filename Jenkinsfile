pipeline {
    agent any
    stages {
        stage('Hai') {
            steps {
                echo 'Hello World1'
                echo "${SAMPLE_URL}"
                echo "${SSH}"
                echo "PERSON = ${PERSON}"
                sh 'nvm --version'
            }
        }
    }
}