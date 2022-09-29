node {

        stage('Demo Terraform') {
            sh '''
                date
          '''

        }
        stage('Terraform init') {
            sh '''
            rm -rf .terraform || true
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
            /usr/local/bin/terraform apply -auto-approve



            '''

        }


}