node('built-in') 
{
    stage('master ontinuous Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('master Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
   }
