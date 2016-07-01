node {
  stage 'build'
  sh 'build something'

  stage 'package'
  docker.build('willcodeforfoo/jenkins-pipeline-test').push()
}
