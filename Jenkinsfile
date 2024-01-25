pipeline {
        agent any
        stages {
            stage ('Clone') {
                steps {
                    git branch: 'main', credentialsId: 'ductvit96', url: 'https://github.com/ductvit96/jenkins-github.git'
			}
		}
	}
}