node {
    stage('Checkout') {
        // Define the steps within the 'Checkout' stage
        checkout([$class: 'GitSCM', branches: [[name: 'develop']], 
                  userRemoteConfigs: [[url: 'git@github.com:edmundtetteh/movies-loader.git']],
                  credentialsId: 'ubuntu-jenkins'])
    }

    // Add more stages or steps as needed
}

// node('dev') {
//     stage('Checkout') {
//         steps {
//             git branch: 'develop',
//                 credentialsId: 'ubuntu-jenkins',
//                 url: 'git@github.com:edmundtetteh/movies-loader.git'
//         }
//     }
// }

