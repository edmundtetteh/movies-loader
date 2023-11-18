def imageName = 'edmundtetteh/movies-loader'

node('dev') {
    stage('Checkout') {
        checkout([$class: 'GitSCM', branches: [[name: 'develop']],
                  userRemoteConfigs: [[url: 'https://github.com/edmundtetteh/movies-loader.git']],
                  credentialsId: 'ubuntu-jenkins'])
    }

    stage('Unit Tests'){
        def imageTest= docker.build("${imageName}-test", "-f Dockerfile.test .")
        sh "docker run --rm -v $PWD/reports:/app/reports ${imageName}-test"
        junit "$PWD/reports/*.xml"
    }

    // Add more stages 
}




