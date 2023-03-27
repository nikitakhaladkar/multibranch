node('built-in') 
{
    stage('traininng Continuous Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('training Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    }
