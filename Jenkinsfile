
node { 
    
    echo 'Hello World' 
    
    stage ('Checkout scm') {
    }
    
    stage ('Initialize') {
              
        echo "HELLO WORLD"

        ansiblePlaybook installation: 'ansible', playbook: 'site.yml'

    }

}


