pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/srijana2437-dev/bottomline.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
    }
}
