pipeline {
    agent any
    stages {

        stage('testing pipeline'){
		steps{
			missfunc()
		}

}
}
}
//def exists = fileExists "/from-jenkins/test.txt"

void missfunc(){
	sh "ls -l"
}
