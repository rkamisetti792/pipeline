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
    }
}