pipeline {
       agent {
                        label 'Node_one'
                    }

    stages {
        stage('git clone') {
         
            steps {
                git credentialsId: 'gt', url: 'https://github.com/keth-naresh/helloworld.git'
            }
        }
        
    }
 }
