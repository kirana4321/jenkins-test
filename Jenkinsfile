pipeline {
    agent any
    stages {

        stage('testing pipeline'){
          steps{
		  step{
			  def controlFile = "/from-jenkins/test.txt"
		  }
		step{
		sh 'pwd'
		    echo 'test1'
		  if (fileExists(controlFile)){
			  echo '${controlFile} exists.'
		  }
		  else{
			  echo "${controlFile} is missing. Sai can mount this file"
			  sh "mount /from-jenkins/test.txt/"
			  echo "continue amma"
		  }
			  
		  }
               // sh 'mkdir from-jenkins'
               // sh 'touch from-jenkins/test.txt'
                }
        }

}
}
