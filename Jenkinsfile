pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Build Starts!'
                //bat "\"C:/Program Files/dotnet/dotnet.exe\" restore \"${workspace}/JenkinsSampleProject.cs\""
                //bat "\"C:/Program Files/dotnet/dotnet.exe\" build \"${workspace}/JenkinsSampleProject.cs\""
                echo 'Build Ends'
            }
        }
		
		stage('Test') {
            steps {
                echo 'Test Starts!'
                // bat "\"C:/Program Files/dotnet/dotnet.exe\" test \"${workspace}/RazorPageTests\""
                echo 'Test Ends'
            }
        }
		
		stage('Deploy') {
            steps {
                echo 'Deploy Starts!'
                //bat "\"C:/Program Files/dotnet/dotnet.exe\" publish \"${workspace}/SampleWebProject\" --output \"C:/tmp/dotnetweb\""
                echo 'Deploy Ends'
            }
        }		
    }
}
