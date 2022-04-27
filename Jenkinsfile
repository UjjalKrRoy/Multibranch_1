node('master') 
{
    stage('Continuous_Download_products') 
	{
    git 'https://github.com/UjjalKrRoy/devops1.git'
	}
    stage('Continuous_Build_products') 
	{
    sh label: '', script: 'mvn package'
	}
}
