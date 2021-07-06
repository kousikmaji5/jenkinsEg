pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withGradle {
                    sh 'gradle build'
                }
            }
        }

        stage ('Testing Stage') {

            steps {
                withGradle {
                    sh 'gradle test'
                }
            }
        }

    

        
    }
}
