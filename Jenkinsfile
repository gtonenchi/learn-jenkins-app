pipeline {
    agent any

    stages {
        stage('w/o docker') {
            steps {
                sh '''
                    echo "Without docker"
                    touch withoutdocker.txt
                    ls -la
                '''
            }
        }
    }
}
//