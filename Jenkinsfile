pipeline {   
    agent any

    stages {   
        stage('dev for my testing branch') { 
            steps { 
               sh 'echo "This is dev branch"' 
            }
        }
     
        stage('dev') { 
            steps { 
               sh 'echo "dev application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
