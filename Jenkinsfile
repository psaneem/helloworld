pipeline {
    /* insert Declarative Pipeline here */
    agent { 
        node { 
            label 'pat' 
              } 
            } 
    stages { 
        stage('Read the README') {
            steps {
                sh "cat demo.txt"
            }
        }
    }       
}
