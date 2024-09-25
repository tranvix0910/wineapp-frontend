pipeline {
    agent any
    
    stages {
        stage('Clone Code') {
            steps {
                git branch: 'main', url: 'https://github.com/username/repository.git'
            }
        }
    }
}
