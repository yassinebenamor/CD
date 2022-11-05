pipeline{
    agent any
    //tools {}
    stages{
        stage('Build'){
            steps{
              sh 'sudo ansible-playbook Ansible/build.yml -i Ansible/inventory/host.yml';
            }
        }
    }
}
