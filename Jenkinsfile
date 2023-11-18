def imageName = 'edmundtetteh/movies-loader'

node('dev') {
    stage('Checkout') {
        checkout([$class: 'GitSCM', branches: [[name: 'develop']],
                  userRemoteConfigs: [[url: 'https://github.com/edmundtetteh/movies-loader.git']],
                  credentialsId: 'ubuntu-jenkins'])
    }

       stage('Unit Tests'){
        sh "docker build -t ${imageName}-test -f Dockerfile.test ."
        sh "docker run --rm ${imageName}-test"
    }

    // Add more stages 
}




