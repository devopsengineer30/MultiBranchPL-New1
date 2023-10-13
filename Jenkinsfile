pipeline {   
    agent any

    stages {   
        stage('sprint122 branch') { 
            steps { 
               sh 'echo "This is sprint1 branch"' 
            }
        }
     
        stage('Test') { 
            steps { 
               sh 'echo "Testing application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
