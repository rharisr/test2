pipeline {
    agent any 
    options{
        timestamps()
        overrideIndexTriggers(true)
        //skipStagesAfterUnstable()
    }
    stages {
        stage("Build parallel "){
            //failFirst true 
            parallel{
                stage('Step1') {
                    steps {
                    echo "hello world Step 1"
                    scripts{
                        currentBuild.result = 'UNSTABLE'
                    }
                    sleep 10
                    }

                }
                stage("Step2"){
                    steps {
                        echo "hello world Step 2"
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
