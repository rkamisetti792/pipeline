pipeline{
    agent{
        label 'master'
    }
    stages{
        stage('Build'){
            when{
                changeset glob: '*.js'
           }
            steps{
                timestamps{
                    echo "Pull Request"
                }
            }
        }
    }
}