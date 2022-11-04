pipeline{
    agent any
    //tools {}
    stages{
        stage('Build'){
            steps{
              sh 'ansible-playbook Ansible/build.yml -i Ansible/inventory/host.yml -b';
            }
        }
    }
}
