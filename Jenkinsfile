pipeline {
    agent any
    tools { 
        maven 'Maven 3_5_4' 
        jdk 'jdk_8' 
    }
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                ''' 
            }
        }

        stage ('Build') {
            steps {
                sh 'mvn clean compile'
            }
        }
    }
}
