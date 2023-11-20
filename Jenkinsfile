pipeline {
    agent any

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
