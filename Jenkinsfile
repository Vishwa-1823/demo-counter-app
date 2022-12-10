pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{
                    
                    git branch: 'main', url: 'https://github.com/Vishwa-1823/demo-counter-app.git'
                }
            }
        }  
    }
}
