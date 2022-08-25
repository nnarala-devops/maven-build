pipeline {
    agent any

    stages {
        stage('Checkout Git repository') {
           steps {
               git branch: 'main', changelog: false, poll: false, url: 'https://github.com/nnarala-devops/maven-build.git'
            }
        }
        stage ('Clean') {

            steps {
                echo 'cleaning the code'
            }
        }
        stage ('Compile') {
            steps {
                echo 'compliling the code'
            }
        }
        stage ('Test') {
            steps {
                echo 'Tesing the code'
            }
        }
    }
}
