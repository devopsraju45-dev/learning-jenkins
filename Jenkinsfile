
pipeline {
    agent any

    stages {

        stage('Parallel Stages') {
            parallel {
                stage('Stage1') {
                    steps {
                        echo 'one'
                        sh 'sleep 10'
                    }
                }
                stage('Stage2') {
                    steps {
                        echo 'one'
                    }
                }
                stage('Stage3') {
                    steps {
                        echo 'one'
                    }
                }
                stage('Stage4') {
                    steps {
                        echo 'one'
                    }
                }
            }
        }

        stage('Two') {
            steps {
                echo 'two'
            }
        }
        stage('Three') {
            steps {
                echo 'three'
            }
        }


    }

}