pipeline {
    agent any
    tools {
        maven 'maven_3.9.1'
    }
    stages {
        stage ('Build') {
            steps {
                echo 'Build Stage'
                bat 'mvn clean package'
            }
        }

        stage ('Deploy') {
            steps {
                echo 'Deploy Stage'
            }
        }
    }
}
