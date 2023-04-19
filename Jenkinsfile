pipeline {
    agent any
    stages {
        stage('performing a dry run') {
            steps {
                sh "ansible-playbook robot-dryrun.yml -e COMPONENT=mongodb -e ansible_user=centos -e ansible_password=DevOps321 -e ENV=pp"
            }
        }

    }

}