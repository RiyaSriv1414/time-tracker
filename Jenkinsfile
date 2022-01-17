pipeline {
    agent any
    environment{
        PATH= "C:\DevTools\apache-maven-3.8.1\bin:$PATH"

    stages {
        stage('Gitcheckout') {
            steps {
                git 'https://github.com/RiyaSriv1414/time-tracker.git'
            }
        }
        stage('Maven Build') {
            steps {
                sh "mvn clean package"
            }
    }
}
