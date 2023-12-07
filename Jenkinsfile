pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                script{
                    sh 'mvn clean install'
                }
            }
           
        }
    }
    post{
        always{
            cleanWs()
        }
       
    }
}
