pipeline 
{
    agent any 
     
      stages {
        stage('pull code') {
           steps {
        git credentialsId: 'Jenkins_Github_int', url: 'https://github.com/SwapnilAD61/registration_portal.git'
          
               }
             }
        stage('build')    
          {        
              steps        
              {             
                  sh "mvn clean package"  
              }       
          }
       }
  }
