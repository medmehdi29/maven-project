pipeline {
    agent any
 tools {
        maven 'Maven 3.5.0'
    }
    stages {
        stage ('clean') {

            steps {

                    sh 'mvn clean install'
                }
            
        }

        stage ('package') {

            steps {

                    sh 'mvn package'
                }
            
        }
        
    }
}


