pipeline {
    agent any
    stages {
	    stage("stage_name"){	
		    steps {
		        sh "echo stage1 step1"
		        sh "echo stage1 step2"
		        sh "echo stage1 step3"
            }
        }
        stage("stage2"){
            steps {
                sh "echo stage2 step1"
                sh "echo stage2 step2"
                sh "echo stage2 step3"
            }
        }
    }
}
