pipeline {
node ('master') {
  checkout scm
  sh 'rm -fR Pipelines'
  sh 'git clone https://github.com/pbache/Pipelines.git'
  def commonpipe = load 'Pipelines/com_test.groovy'
  commonpipe.comm_test()
}
