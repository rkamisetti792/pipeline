pipeline{
    agent{
<<<<<<< HEAD
        label: 'master'
=======
        label 'master'
>>>>>>> 9eb0b02bafccf11d283af7126a98a9b4ad3bfbb7
    }
    stages{
        stage('Build'){
            when{
<<<<<<< HEAD
                changeset glob: '*.js'
=======
                changeRequest title:"Pull Request"
            }
            steps{
                timestamps{
                    echo "Pull Request"
                }
>>>>>>> 9eb0b02bafccf11d283af7126a98a9b4ad3bfbb7
            }
        }
        stage("Test"){
            steps{
<<<<<<< HEAD
                echo "Hello ChangeSet"
=======
                timestamps{
                    echo "Test Pull Request"
                }
>>>>>>> 9eb0b02bafccf11d283af7126a98a9b4ad3bfbb7
            }
        }
    }
}