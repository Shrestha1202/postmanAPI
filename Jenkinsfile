  
pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                bat 'newman run MyCollection.postman_collection.json'
            }
        }
    }
}