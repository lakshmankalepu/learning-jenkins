import jenkins.model.*
jenkins = Jenkins.instance


pipeline {
    agent {
       label node2
    }

    stages {
        stage('Build') {
            steps {
                echo 'This is from Build'
            }
        }
        stage('Test') {
            steps {
                echo 'This is from Test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'This is from Deploy'
            }
        }
    }
}
