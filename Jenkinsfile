node {
	stage ('build'){
		if(env.TAG_NAME != null){
			println("we are building tag ${env.TAG_NAME}")
		}
		else {
			println("we are building branch")
		}
		if(env.TAG_NAME == "release-2.0"){
			println("we are building release-2.0")
		}
	}
}
