pipeline{
    agent any
    stages {
        stage('verify BRACNC-Sravangit') {
            steps {

            echo "$GIT_BRANCH"
            }
        }

        stage('docker build') {
            steps {
                sh(script: 'docker images -a')
            }
        }
    
    

    
    }
}