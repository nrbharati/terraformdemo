node {

        stage('Demo Terraform') {
            sh '''
                ${env.BUILD_ID}  ${env.JENKINS_URL}
          '''

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