
pipeline {
    agent any
 
    options {
        skipDefaultCheckout(true)
    }
 
        stage('Deploy') {
            steps {
                echo '> Deploying the application ...'
                sh 'ansible-playbook'
            }
        }