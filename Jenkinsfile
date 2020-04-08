
node {
    // Get Artifactory server instance, defined in the Artifactory Plugin administration page.
    def server = Artifactory.server "artifactory"
    // Create an Artifactory Maven instance.
    def rtMaven = Artifactory.newMavenBuild()
    def buildInfo
    
 rtMaven.tool = "maven"
	

    stage('Clone sources') {
        build job: 'code-analysis'
    }
	
	
        tools {
          maven 'maven'
        }
        
          
    }
	 
