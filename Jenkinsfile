node('workers'){
  stages {
    stage('Checkout'){
      steps {
        git branch: 'develop',
            credentialsId: 'jenko',
            url: 'git@github.com:tomislav993/Loader.git'
       }
    }
  }
}