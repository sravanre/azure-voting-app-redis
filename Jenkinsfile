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

        stage(' docker run new containter'){
            steps {
                sh(script:"""
                 docker run -it nginx
                 uptime
                """ )
            }
        }
    
    

    
    }
}