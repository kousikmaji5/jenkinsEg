pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withGradle {
                    sh './gradlew build'
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


        stage ('Deployment Stage') {
            steps {
                withGradle {
                    sh 'gradle deploy'
                }
            }
        }
    }
}
