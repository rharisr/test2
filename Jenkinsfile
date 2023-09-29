pipeline {
    agent any 
    stages {
        stage("Build"){
            when {
                //buildingTag()
                //tag "release-*"
                changelog '.*rel_txt.*' 
            }
            steps{
                echo "Hello world Build tag "
            }
            
        }
    }
}
