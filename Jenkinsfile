pipeline {
    agent any 
    options{
        timestamps()
        overrideIndexTriggers(true)
    }
    stages {
        stage("Build parallel "){
            //failFirst true 
            parallel{
                stage('Step1') {
                    steps {
                        
                    echo "Step 1"
                    sleep 10

                    }
                }
                stage("Step2"){
                    steps {
                        echo "Step 2"
                        sleep 10
                    }
                }
                stage("Step3"){
                    steps {
                        echo "Step 2"
                        sleep 10
                    }
                }
            }
        }
    }
}
