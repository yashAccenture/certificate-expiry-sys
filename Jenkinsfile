pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                script{
                    bat 'mvn clean install' //for linux sh
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
