  
pipeline {
    agent any
    environment {
		 PATH="C:\Users\Vishal Bansal\AppData\Roaming\npm:$PATH"
	}
    stages {
        stage('Build') {
            steps {
                bat 'newman run MyCollection.postman_collection.json'
            }
        }
    }
} 



