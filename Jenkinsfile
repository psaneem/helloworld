pipeline {
    /* insert Declarative Pipeline here */
    
     parameters {
        string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
        choice(name: 'CHOICE', choices: ['One', 'Two', 'Three'], description: 'Pick something')
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
         stage('Read the Parameters') {
            steps {
                sh "echo ${params.PERSON}"
            }
        }
        stage('Read the Choice') {
            steps {
                sh "echo ${params.CHOICE}"
            }
        }
    }       
}
