// pipeline{
//     agent{
//         label 'docker'
//     }

//     stages{
//         stage('Build Docker image'){
//             steps{
//                 script{
//                     sh 'docker build -t mowalid29/docker-react -f dockerfile.dev . '    
//                 }
//             }
//         }
//         stage('Run Tests'){
//             steps{
//                 script{
//                     env.DOCKER_BUILDKIT = 1
//                     sh 'docker run -e CI=true mowalid29/docker-react npm run test'    
//                 }
//             }
//         }
//     }
// }
