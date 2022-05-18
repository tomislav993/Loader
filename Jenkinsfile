node('workers'){
    stage('Checkout'){
      steps {
        git branch: 'develop',
            credentialsId: 'jenko',
            url: 'git@github.com:tomislav993/Loader.git'
       }
    }
}