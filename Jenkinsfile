pipeline{
    agent any
    //tools {}
    stages{
        stage('Build'){
            steps{
              sh 'Ansible-playbook ansible/build.yml -i ansible/inventory/host.yml';
            }
        }
    }
}
