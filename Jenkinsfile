

pipeline
{
    agent any
    
    stages
    {
        
        stage('continuousdownload'){
                steps
                {
                    git branch: 'test', url: 'https://github.com/rameshbabuts/mavenproject-1.git'
                    
                }
                
            
        }
        stage('continuousbuild'){
                steps
                {
                    sh "mvn package"
                    
                }
                
                         
        }
    }
}

