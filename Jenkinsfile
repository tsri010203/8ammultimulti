node('built-in') 
{
    stage('Continuous Download_Master') 
	{
          git 'https://github.com/tsri010203/mycode.git'
	}
    stage('Continuous Build_Master') 
	{
    sh label: '', script: 'mvn package'
	}
}
