// node('dev') {
//     stage('Checkout') {
//         steps {
//             git branch: 'develop',
//                 credentialsId: 'ubuntu-jenkins',
//                 url: 'git@github.com:edmundtetteh/movies-loader.git'
//         }
//     }
// }

node('dev'){
    stage('Checkout'){
        checkout scm
    }
}