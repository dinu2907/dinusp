pipeline{
      agent any{
         stages('checkout'){
           steps { 
         checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/dinu2907/dinusp.git']]])
           }
        }
}
}
