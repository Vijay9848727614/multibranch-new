pipeline {   
    agent any

    stages {   
        stage('dev for testing branch') { 
            steps { 
               sh 'echo "This is dev branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
