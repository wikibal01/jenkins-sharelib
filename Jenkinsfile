String GHEAccess = 'jenkinsPAT'

library identifier: 'jenkins-sharedlib-newtrn@master', retriever: modernSCM([$class: 'GitSCMSource',
	remote: 'https://github.com/arehmandev/trn-project.git',
	credentialsId: GHEAccess])

@Library('my-shared-library') _

evenOrOdd(currentBuild.getNumber())
