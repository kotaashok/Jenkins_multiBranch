node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/kotaashok/Maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
