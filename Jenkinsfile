node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/jtaku4/optclab.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
`}
}
