def pipeline
node ('master') {
  $buildenv = ${params.DEPLOY_ENV}
  sh 'echo "Will deploy to $buildenv"'
}
