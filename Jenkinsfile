pipeline {
    agent any 
    stages {
        stage("Build"){
            when {
                //buildingTag()
                //tag "release-*"
                //changelog '.*rel_txt.*' 
                changeRequest()
            }
            steps{
                echo "Hello world Build tag "
            }
            
        }
    }
}
