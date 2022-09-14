import java.text.SimpleDateFormat

pipeline {
//     agent any
//     environment {
//         imageUrl = "$ecsRegistry:${BUILD_NUMBER}"
//     }
    stages {
            stage('Cmd Test') {
                steps {
                    sh "pwd"
                    sh "ls"
                }
            }
//         stage('Docker Build') {
//             steps {
//                 sh "docker build  --build-arg SPRING_ENV=${springEnv} -t $imageUrl ."
//             }
//         }
//         stage("Docker Push") {
//             steps {
//                 withAWS(credentials:"$awsCredentials") {
//                     script {
//                         def login = ecrLogin()
//                         sh "${login}"
//                     }
//                 }
//                 sh "docker push $imageUrl"
//             }
//         }
//         stage('kubectl deployment apply') {
//             steps {
//                 sh 'IMAGE_URL=${imageUrl} REPLICAS=${REPLICAS} BUILD_NUMBER=${BUILD_NUMBER} envsubst < $podName-deployment.yml | kubectl apply -f -'
//             }
//         }
//         stage('docker ps,image delete') {
//             steps {
//                 sh 'docker rm $(docker ps -aq) -f || true'
//                 sh 'docker rmi $(docker images -aq) -f || true'
//             }
//         }
//         stage('Trigger ManifestUpdate') {
//             steps {
//                 echo "triggering updatemanifestjob"
//                 build job: 'updatemanifest', parameters: [string(name: 'tagNumber', value: "${BUILD_NUMBER}"),string(name: 'springEnv', value: "${springEnv}"),string(name: 'imageUrl', value: "${imageUrl}"),string(name: 'podName', value: "${podName}"),string(name: 'REPLICAS', value: "${REPLICAS}")]
//             }
//
//         }

    }

 }
