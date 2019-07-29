pipeline {
    agent any
    stages {

        stage('testing pipeline'){
		steps{
			script {
		missfunc()
		sh "pwd"
                def folder = fileExists 'from-jenkins/test.txt'
                    if( folder) {
                        echo "Yes"
                    } else {
                        echo "File doesn't exist" 
                    }
        		}
		}

}
}
}
//def exists = fileExists "/from-jenkins/test.txt"

void missfunc(){
	sh "ls -l"
}
