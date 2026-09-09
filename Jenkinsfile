pipeline {
    agent any

    stages {
        stage('stage 1'){
            steps{
                echo "this is a message"

            }

        }
        stage('stage 2'){
            steps{

                    
                sh '''
                    sleep 5
                    ls -lrt
                    pwd

                '''

            }

        }




    }
}