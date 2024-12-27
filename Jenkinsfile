pipeline{
    agent any
    stages {
        stage("First Stage"){
            steps{
                script{
                    echo "Hello"
                    sh '''
                        echo "${env.BRANCH_NAME}"
                    '''
                }
            }
        }
    }
}