pipeline {
    agent any 
    stages {
        stage("Build"){
            when {
                //buildingTag()
                tag "release-*"
                
            }
            steps{
                echo "Hello world Build tag "
            }
            
        }
    }
}
