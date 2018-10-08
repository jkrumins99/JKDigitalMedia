
Jenkinsfile (Declarative Pipeline)

pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
        
        stage('Test') {
            steps {
                sh 'echo "This is a test"; exit 0'
            }
        }
    }
}

