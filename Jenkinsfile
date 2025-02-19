pipeline {
    agent any
    stages {
        stage('Clone Code') {
            steps {
                git branch: 'main', url: 'https://github.com/rabeeht2/jenkins.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
    }
}
