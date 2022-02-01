pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'echo holajesus'
            timeout(time: 1, unit: 'MINUTES') {
                    bat 'echo ya espere 1 minuto'
            	}                        
            }
        }
    }
}