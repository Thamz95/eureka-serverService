pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withMaven(maven : 'maven_3_5_4') {
                   echo 'hi im building here'
                }
            }
        }

        
    }
}
