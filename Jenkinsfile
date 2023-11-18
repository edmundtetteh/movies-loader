// node('dev') {
//     stage('Checkout') {
//         steps {
//             checkout([$class: 'GitSCM', branches: [[name: 'develop']], 
//                       userRemoteConfigs: [[url: 'https://github.com/edmundtetteh/movies-loader.git']],
//                       credentialsId: 'GitHub'])
//         }
//     }

//     // Add more stages or steps as needed
// }

// pipeline {
//     agent { label 'dev' }

//     stages {
//         stage('Checkout') {
//             steps {
//                 script {
//                     checkout([$class: 'GitSCM', branches: [[name: 'develop']],
//                               userRemoteConfigs: [[url: 'https://github.com/edmundtetteh/movies-loader.git']],
//                               credentialsId: 'ubuntu-jenkins'])
//                 }
//             }
//         }

//         // Add more stages or steps as 
//     }
// }

// node('dev') {
//     stage('Checkout') {
//         checkout([$class: 'GitSCM', branches: [[name: 'develop']],
//                   userRemoteConfigs: [[url: 'https://github.com/edmundtetteh/movies-loader.git']],
//                   credentialsId: 'ubuntu-jenkins'])
//     }

//     // Add more stages or steps as needed
// }

node('dev') {
    stage('Checkout') {
        checkout([$class: 'GitSCM', branches: [[name: 'develop']],
                  userRemoteConfigs: [[url: 'git@github.com:edmundtetteh/movies-loader.git']],
                  credentialsId: 'interation-jenkins'])
    }

    // Add more stages or steps as needed
}




// node('dev') {
//     stage('Checkout') {
//         steps {
//             git branch: 'develop',
//                 credentialsId: 'ubuntu-jenkins',
//                 url: 'https://github.com/edmundtetteh/movies-loader.git'
//         }
//     }

//     // Add more stages or steps as needed
// }


// node {
//     stage('Checkout') {
//         // Define the steps within the 'Checkout' stage
//         checkout([$class: 'GitSCM', branches: [[name: 'develop']], 
//                   userRemoteConfigs: [[url: 'git@github.com:edmundtetteh/movies-loader.git']],
//                   credentialsId: 'ubuntu-jenkins'])
//     }

//     // Add more stages or steps as needed
// }


// stage('Checkout') {
//     steps {
//         git branch: 'develop',
//             credentialsId: 'ubuntu-jenkins',
//             url: 'https://github.com/edmundtetteh/movies-loader.git'
//     }
// }


