pipeline {
         agent any
         stages {
	             stage ('Run playbook') {
                 step {} 
                    ansiblePlaybook(
                       inventory: 'hosts',
                       playbook: 'playbook.yml'
                    )
                 }
            }  
        }
}