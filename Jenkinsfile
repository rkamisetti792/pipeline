pipeline{
    agent any
    stages{
        stage('Build'){
            when{
                tag '3.0'
            }
            steps{
                echo "Build with Tags"
            }
        }
    }
}