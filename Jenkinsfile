node {
  //Stage 1: Checkout Code from Git
    stage('Application Code Checkout from Git') {
        sh("echo Hello")
    }
    //Stage 2: Deploy Application on MiniKube
    stage('Deploy Application on MiniKube') {
                sh("kubectl apply -f elastic-stack/kibana-service.yaml")
        }
   }