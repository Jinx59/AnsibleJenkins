node {
	// stage 'Checkout' {
	// 	checkout scm
    // }

	stage 'Build' {
		git url: 'https://github.com/Jinx59/AnsibleJenkins.git'
        ansiblePlaybook(
           inventory: 'hosts',
           playbook: 'playbook.yml'
    )
    }
}