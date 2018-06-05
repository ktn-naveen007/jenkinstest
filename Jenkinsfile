pipeline{
	agent { node { label 'master' } }
	stages{
		stage("build"){
			steps{
				bat """
					mvn exec:java
				"""
				}
			}
	}
}