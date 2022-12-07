pipeline {
  
    agent any

    stages {
      
        stage("build"){
          
            steps {
              // build the maven project  
              sh "mvn -Dmaven.test.failure.ignore=true clean package"
                // setting up limits to the number of stored results
                // setting up git integration
                // "Project build setup" - compile?
                // "setting up test runs" - preconditions?
                // "Configuring post- and pre-build tasks"
                // Configuring parametrization (browser, credentials etc.)
                // "Saving and publishing build artifacts (logs\screenshots)"
            }
    
        }
        stage("test"){

            steps {
                 // Manual build start
                 // Scheduled build (knowledge of cron expressions)
                 // Starting a build from another build (2nd build starts after the (un)successful build of the 1st, etc.)
                 // Run build if there are any changes in VCS
            }
        }
    }
}

