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
                echo "Pull Request"
            }
        }
    }
}