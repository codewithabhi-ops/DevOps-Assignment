pipeline {
    agent any


        stages {
            stage("clone-repo"){
                steps {
                    git branch: 'main', credentialsId: 'coder_abhishek', url: 'https://github.com/codewithabhi-ops/DevOps-Assignment.git'
                }
            }
        }
}


