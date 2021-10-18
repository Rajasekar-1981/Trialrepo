pipeline {
    agent any

    stages {
        stage('tree install') {
            steps {
               ansiblePlaybook become: true, installation: 'ansible', inventory: 'inventory', playbook: 'tree_install_playbook'
            }
        }
    }
}
