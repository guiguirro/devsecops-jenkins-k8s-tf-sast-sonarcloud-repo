pipeline {
  agent any
  tools { 
        maven 'Maven_3_5_2'  
    }
   stages{
    stage('CompileandRunSonarAnalysis') {
            steps {	
		sh 'mvn clean verify sonar:sonar -Dsonar.projectKey=dvldvldvldvldvldvldvl -Dsonar.organization=dvldvldvldvldvldvldvl -Dsonar.host.url=https://sonarcloud.io -Dsonar.token=f90b09f8c58d0f0c898e35b34ffe6de0c1c0a9c8'
			}
        } 
  }
}
