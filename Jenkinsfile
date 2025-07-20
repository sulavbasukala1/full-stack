pipeline {
    agent any
    stages {
        stage('fetching code from github'){
          steps {
            git url: 'https://github.com/sulavbasukala1/full-stack'
    }
}
        stage ('brunning container'){
          steps {
    sh 'ansible-playbook -i inventory playbook.yml'
}
}
    }
}



        
