pipeline {
    agent any
    tools {
        gradle 'gradle'
        jdk 'JDK'
    }
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Harshini-Medha/MyGradleApp07.git'
            }
        }
        stage('Build') {
            steps {
                sh 'gradle build'
            }
        }
        stage('Test') {
            steps {
                // probably missing here or somewhere else
            }
        }
    }  // make sure this closes stages
}  // make sure this closes pipeline
