node {
  stage "Checkout"
  checkout scm

  stage 'Build'
  sh 'build something'

  stage 'Package'
  docker.build('willcodeforfoo/jenkins-pipeline-test').push()
}
