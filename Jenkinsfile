pipeline {
    agent any
    stages {
         stage('Helm Chart Execution'){
          steps{
        	  sh '/home/ubuntu/chart.sh'
                }
	}	
	stage('Test'){
          steps{
        	  sh 'python3 /home/ubuntu/Third.py'
                }	
	           }
         }
}