pipeline {
    agent any
    
    stages {
        stage('Clone Code') {
            steps {
                // Clone repository từ GitHub
                git branch: 'main', url: 'https://github.com/username/repository.git'
            }
        }
    }
}
