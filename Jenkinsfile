node('master'){
    stage('initialize'){
        checkout scm
    }
    stage('compile'){
                    bat """
    					mvn compile -Dmaven.skipTests=true
    				"""
    }
    stage('unittest'){
                    bat """
        					mvn test
        				"""
    }
    stage('package'){
     bat """
        					mvn package
        				"""
    }
}

