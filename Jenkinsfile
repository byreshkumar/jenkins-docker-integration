pipeline {
	stages {
		stage('Deployment'){
				steps{
					echo 'welcome to jenkins and docker integration'
				}
			}
		}

}

//Helper Methods

void executeCmd(String CMD){
	if(isUnix()){
		sh "echo linux"
		sh CMD
	}
	else{
		 bat "echo windows"
		 bat CMD
	}
}



