pipeline{
    agent{
        label 'master'
    }
    stages{
        stage('Build'){
            when{
                changeRequest title "Pull Request"
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