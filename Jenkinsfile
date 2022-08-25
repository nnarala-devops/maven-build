pipeline {
    agent any

    stages {
        stage('Checkout Git repository') {
           steps {
               git branch: 'main', changelog: false, credentialsId: '0bc0fed2-a14c-4ed0-a5c1-562fc5af2e86', poll: false, url: 'https://github.com/nnarala-devops/maven-build.git' 
            }
        }

        stage ('Clean') {

            steps {
                sh 'cleaning the code'
            }
        }
        stage ('Compile') {
            steps {
                sh 'compliling the code'
            }
        }
        stage ('Test') {
            steps {
                sh 'Tesing the code'
            }
        }
    }
}
