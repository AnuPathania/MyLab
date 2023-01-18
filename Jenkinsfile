pipeline{
    //Directives
    agent any
    tools{
           maven "MAVEN"   
    }
    stages {
        // Specify various stage with in stages

        // stage 1. Build
        stage ('Build'){
            steps {
                 sh 'mvn clean package'
                
            }
        }

        // Stage2 : Testing
        stage ('Test'){
            steps {
                echo ' testing......'

            }
        }
        
        
    }

}
