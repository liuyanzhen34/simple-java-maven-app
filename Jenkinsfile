pipeline {
    agent any
    stages {
        stage('Bulid') {
            steps {
                 sh 'mvn -B -DskipTests clean package'
            }
        }    
    }
}

