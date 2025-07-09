pipeline {
    agent any

    stages {
        stage('Read Text File') {
            steps {
                echo 'Reading contents of hello.txt:'
                sh 'cat hello.txt'
            }
        }
        stage('Build') {
              steps {
                  echo '🎉 Hello! This is my first Jenkins build.'
              }
        }
    }
}
