pipeline{
    //Directives
    agent any
    tools {
        maven 'Maven 3.3.9' 
    }

    stages {
        // Specify various stage with in stages

        // stage 1. Build
        stage ('Build'){
            steps {
                 echo ' building......'
                sh "mvn clean verify"
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
