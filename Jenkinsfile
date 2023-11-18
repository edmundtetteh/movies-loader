node('dev') {
    stage('Checkout') {
        checkout([$class: 'GitSCM', branches: [[name: 'develop']],
                  userRemoteConfigs: [[url: 'https://github.com/edmundtetteh/movies-loader.git']],
                  credentialsId: 'ubuntu-jenkins'])
    }

    // Add more stages 
}




