pipeline {
    agent any 
    stages {
        stage("Build"){
            when {
                buildTag()
                
            }
            steps{
                echo "Hello world Build tag "
            }
            
        }
    }
}
