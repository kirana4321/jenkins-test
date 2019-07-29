pipeline {
    agent any
    stages {

        stage('testing pipeline'){
		steps{
			sh 'pwd'
			step{
				if (exists) {
    					sh "LINUX SHELL COMMAND"
				} 
			     else {
    					echo "File doesn't exist"
				}
			}

               // sh 'mkdir from-jenkins'
               // sh 'touch from-jenkins/test.txt'
        }

}
}
}
def exists = fileExists '/root/elp/test.php'
