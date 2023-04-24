pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           git "https://github.com/sureshtalari/hello-world.git" 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
