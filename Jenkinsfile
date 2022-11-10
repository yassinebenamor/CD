pipeline{
    agent any
    //tools {}
    stages{
        stage('Build'){
            steps{
              sh 'ansible-playbook ansible/build.yml -i ansible/inventory/host.yml';
            }
        }
    }
}
