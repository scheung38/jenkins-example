pipeline {
    agent any

    stages {

        stage('My echo Stage') {
            steps {
                sh 'echo $HOME'
            }
        }

        stage('Second Stage') {
            steps {
                sh 'pwd'
            }
        }

    }
}