/* Requires the Docker Pipeline plugin */
//node('Normal') { //To point to specific jenkins labeled node
node {
    checkout scm
    stage('Build') {
     //   docker.image('maven:3.3.3').inside {
             withMaven(
                 maven: 'maven_3.5.4', mavenLocalRepo: '/maven/repo') {
                sh 'mvn clean compile'
              }
     //   }
    }
}
