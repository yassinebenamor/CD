pipeline{
    agent any
    //tools {}
    stages{
        stage('Build'){
            steps{
              sh 'Ansible-playbook Ansible/build.yml -i Ansible/inventory/host.yml';
            }
        }
    }
}
