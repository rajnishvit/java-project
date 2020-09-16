pipeline {
    
    agent any
    stages {
        stage("build") {
            steps {
                sh 'mvn -Dskiptest clean package'
            }
        }
        stage("test") {
            steps {
                sh 'mvn test'
            }
        }
    }
}
