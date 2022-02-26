pipeline {
    /* insert Declarative Pipeline here */
    
     parameters {
        string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
    }
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
