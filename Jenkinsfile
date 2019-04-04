pipeline {
	stage ('Run playbook') { 
        ansiblePlaybook(
           inventory: 'hosts',
           playbook: 'playbook.yml'
        )
    }
}