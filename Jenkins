pipeline 
	{	
	agent any
	stages
		{
		stage("git")
			{
			steps
				{
				git ""https://github.com/Karthikkl2001/build2.git
				}
			}
		stage("run")
			{
			steps
				{
				sh "mvn clean"
				sh "clean install"
				}
			}
		}
	}
