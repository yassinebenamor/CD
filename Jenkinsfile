pipeline{
    agent any
    tools {
    ansible 'ansible'
    }
    stages{
        stage('Build'){
            steps{
              sh 'ansible-playbook Ansible/build.yml -i Ansible/inventory/host.yml"';
            }
        }
    }
}
