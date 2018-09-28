/* Requires the Docker Pipeline plugin */
node('Normal') {
    checkout scm
    stage('Build') {
     //   docker.image('maven:3.3.3').inside {
            sh 'mvn --version'
     //   }
    }
}
