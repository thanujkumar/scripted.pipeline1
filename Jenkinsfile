/* Requires the Docker Pipeline plugin */
//node('Normal') { //To point to specific jenkins labeled node
node {
    checkout scm
    stage('Build') {
     //   docker.image('maven:3.3.3').inside {
            sh 'mvn --version'
     //   }
    }
}
