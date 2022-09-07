node('Built_in') 
{
    stage('Continuous Download_goudru') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_goudru') 
	{
    sh label: '', script: 'mvn package'
	}
}
