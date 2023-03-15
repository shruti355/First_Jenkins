pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                git 'https://github.com/shruti355/Jenkins.git'
            }
        }
        stage('Test') { 
            steps {
                echo 'Clone DONE'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Deploying'
            }
        }
    }
}
