pipeline {
    agent any
    stages {
        // stage('fmt') {
        //     steps {
        //         sh "terraform fmt"
        //     }
        // }
        // stage('init') {
        //     steps {
        //         sh "terraform init"
        //     }
        // }
        // stage('plan') {
        //     steps {
        //         sh "terraform plan -input=false"
        //     }
        // }
        // stage('apply') {
        //     steps {
        //         sh "terraform apply -input=false -auto-approve"
        //     }
        // }
        stage('destroy') {
            steps {
                sh "terraform destroy -input=false -auto-approve"
            }
        }
    }
} 