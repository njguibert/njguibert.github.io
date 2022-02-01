pipeline {
    agent any
    stages {
        stage('build') {
            steps {
            	retry(3){
            		bat 'go build C:\Users\jesus.guibert\go\helloworld\main.go'
            	}
            timeout(time: 3, unit: 'MINUTES') {
                    bat 'echo ya espere 3 minuto'
            	}                        
            }
        }
    }
}