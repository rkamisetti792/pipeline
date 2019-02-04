pipeline{
    agent{
        label 'master'
    }
    stages{
        stage('Build'){
            when{
                changeRequest()
            }
            steps{
                timestamps{
                    echo "Pull Request"
                }
            }
        }
        stage("Test"){
            steps{
                timestamps{
                    echo "Test Pull Request"
                }
            }
        }
    }
}