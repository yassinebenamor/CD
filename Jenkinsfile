pipeline{
    agent any
    tools {
    nodejs 'nodejs'
    }
    stages{
        stage('Build'){
            steps{
              sh 'npm install --save-dev @angular-devkit/build-angular'
              sh 'ansible-playbook ansible/build.yml -i ansible/inventory/host.yml';
            }
        }
    }
}
