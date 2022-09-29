pipeline {
    agent any
    stages {
        stage('Demo Terraform') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }

        }
        stage('Terraform init') {
            sh '''
            /usr/local/bin/terraform init



            '''
        }
        stage('Terraform plan') {
             sh '''
            /usr/local/bin/terraform plan



            '''
        }

        stage('Terraform apply'){
         sh '''
            /usr/local/bin/terraform apply



            '''

        }

    }
}