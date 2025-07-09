pipeline {
    agent any

    stages {
        stage('Read Text File') {
            steps {
                echo 'Reading contents of myfile.txt:'
                sh 'cat myfile.txt'
            }
        }
        stage('Build') {
              steps {
                  echo '🎉 Hello! This is my first Jenkins build.'
              }
        }
    }
}
