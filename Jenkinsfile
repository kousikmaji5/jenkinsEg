pipeline {
    agent any

    stages {
        stage ('Project 1 Stage 1') {

            steps {
                withGradle {
                    sh 'gradle build'
                }
            }
        }

        stage ('Project 1 Stage 2') {

            steps {
                withGradle {
                    sh 'gradle test'
                }
            }
        }

    

        
    }
}
