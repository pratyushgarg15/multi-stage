pipeline{
    agent any
    stages{
        stage("git pull"){
            steps{
                script{
                    git branch: "master", changelog: false, url: "https://github.com/pratyushgarg15/multi-stage.git" 
                } 
            }  
        }

        stage("build and run docker"){
            steps{
                script{
                    sh "pwd"
                }
            }
        }
    }
}

