pipeline {
    agent any
    stages {
        stage('One') {
                steps {
                        echo 'Hi, this is Maven  from Git'
			
                }
        }

     Stage('Build'){
         Steps {
           sh "mvn -version"
           sh "mvn clean install"
         }

}
    }
}