pipeline{
    agent any
    stages{
        stage('Build'){
            when{
                buildingTag()
            }
            steps{
                echo "Build with Tags"
            }
        }
    }
}