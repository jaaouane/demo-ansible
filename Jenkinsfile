
node { 
    
    echo 'Hello World' 
    
    stage ('Checkout scm') {
        checkout scm
    }
    
    stage ('Initialize') {
              
        echo "HELLO WORLD"

        ansiblePlaybook installation: 'ansible', inventory: 'inventory/dev', playbook: 'site.yml'

    }

}


