node(){
    stage('Cloning Git') {
        checkout scm
    }
        
   
    stage('Build') {
        nodejs('nodejs') {
            sh 'npm run build'
            echo "Build completed"
        }
        
    }

   
