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
    stage('training Continuous deploy') 
    {
    sh 'scp /home/ec2-user/.jenkins/workspace/devlopment/webapp/target/webapp.war ec2-user@172.31.31.224:/var/lib/tomcait/webapps/testenv.war'
    }





    }
