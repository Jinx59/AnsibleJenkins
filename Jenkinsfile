pipeline {
         agent any
         stages {
	             stage ('Run playbook') { 
                 ansiblePlaybook(
                    inventory: 'hosts',
                    playbook: 'playbook.yml'
                )
            }  
        }
}