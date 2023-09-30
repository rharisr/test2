pipeline {
    agent any 
    stages {
        stage("Build parallel "){
            failFirst true 
            parallel{
                stage('Step1') {
                    echo "Step 1"
                    sleep 10
                }
                stage("Step2"){
                    echo "Step 2"
                    sleep 10
                }
                stage("Step3"){
                    echo "Step 3"
                    sleep 10
                }
            }
        }
    }
}
