pipeline{
	agent none
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