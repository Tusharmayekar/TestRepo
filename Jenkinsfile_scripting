node {
	stage 'Checkout'
		checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/Tusharmayekar/TestRepo.git']]])

	stage 'Build'
		echo "Inside buid stage"

	stage 'Archive'
		echo "Packaging ..."

}
