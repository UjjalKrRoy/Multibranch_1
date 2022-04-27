node('master') 
{
    stage('Continuous_Download_Master') 
	{
    git 'https://github.com/UjjalKrRoy/devops1.git'
	}
    stage('Continuous_Build_Master') 
	{
    sh label: '', script: 'mvn package'
	}
}
