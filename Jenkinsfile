pipeline{
    agent any
    stages{
        stage('Build'){
            when{
                tag '6.0'
            }
            steps{
                echo "Build with Tags"
            }
        }
    }
}