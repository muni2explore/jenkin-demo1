pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                displayNodeVersion()
            }
        }
    }
}

void displayNodeVersion() {
    sh '''
    node --version
    ls
    '''
}
