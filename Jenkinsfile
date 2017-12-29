
//ui 
/*
        @Library('PSL') _
	def common_jenkins = new ors.utils.common_jenkins(steps, env)
	def common_scm = new ors.utils.common_scm(steps, env)

	 //   environment {
			
			def TEAM_SLACK_CHANNEL="#spg-feynman-ci"
			def TEAM_EMAIL="m2s6m0x4t8p6v0q0@autodesk.slack.com"
			def SERVICE_ACCOUNT=credentials('svc_p_account_id')
			def VAULT_PATH = 'spg/feynman-dev/aws/adsk-eis-feynman-dev/sts/admin'
			def CDN="s3://cdn-dev-manage.autodesk.com"
			def NPM_REGISTRY="https://art-bobcat.autodesk.com/artifactory/"
			def NPM_AUTH="api/npm/auth"
			def NPM_VIRTUAL_REPO="api/npm/autodesk-npm-virtual/"
			def BUILD_CONTAINER_IMAGE="autodesk-docker.art-bobcat.autodesk.com:10873/team-account/build-npm:latest"
			def DEPLOY_CONTAINER_IMAGE="autodesk-docker.art-bobcat.autodesk.com:10873/team-spg/bedrock-build-terraform:latest"
			def VAULT_ADDR = 'https://vault.aws.autodesk.com'
			def BUILD_INFO="${env.JOB_NAME} ${env.BUILD_NUMBER} \n ${env.BUILD_URL}";
			def SLACK_TOKEN=credentials('ors_slack_token')
			def CI=true
			// Build Configuration
			def BUILD_IMAGE = 'node:8'
			def BUILD_INFO_LAMBDA = "${env.JOB_NAME}-${env.BUILD_NUMBER}\n${env.BUILD_URL}"

			// Deploy Configuration
			def DEPLOY_TOOLS_IMAGE = 'autodesk-docker.art-bobcat.autodesk.com:10873/team-spg/bedrock-build-terraform:latest'

			// Notifications
			def TEAM_SLACK_CHANNEL = '#spg-feynman-ci'

			// Build Status
			def SUCCESS = 'SUCCESS'
			def isMasterBranch = false
			
			*/
			
pipeline {
node ('master') {
  checkout scm
  def buildenv = "${params.DEPLOY_ENV}"
  sh 'rm -fR Pipelines'
  sh 'git clone https://github.com/pbache/Pipelines.git'
  def commonpipe = load 'Pipelines/Common.groovy'
  //commonpipe.prep_common("${buildenv}")
  //commonpipe.prep_common("${buildenv}")
  //commonpipe.prep_common("${buildenv}")
}
