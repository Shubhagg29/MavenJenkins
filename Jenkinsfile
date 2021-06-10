pipeline {
    agent any
    stages {
        stage('One') {
                steps {

                        echo 'Hi, this is Maven  from Git'

                        echo 'Hi, This is Starting for jenkins learning'			
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
