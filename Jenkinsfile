pipeline {
         agent any
         stages {
	             stage ('Run playbook') {
                 steps {
                    ansiblePlaybook(
                       inventory: 'hosts',
                       playbook: 'playbook.yml'
                    )
                 }
            }  
        }
}