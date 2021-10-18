pipeline {
    agent any

    stages {
        stage('tree install') {
            steps {
                ansiblePlaybook become: true, installation: 'ansible', inventory: '/home/ansible/jenkins_playbooks/inventory', playbook: '/home/ansible/jenkins_playbooks/tree_install_playbook'
            }
        }
    }
}
