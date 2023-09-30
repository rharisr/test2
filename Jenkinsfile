pipeline {
    agent any 
    stages {
        stage("Build"){
            when {
                //buildingTag()
                //tag "release-*"
                //changelog '.*rel_txt.*' 
                //changeRequest  title:"when-pr"
                changeset glob: "*.js"

            }
            steps{
                echo "Hello world Build tag "
            }
            
        }
    }
}
