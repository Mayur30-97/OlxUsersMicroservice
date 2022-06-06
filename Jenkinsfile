pipeline {
    agent any

    stages {
         stage('Checkout') {
            steps {
               git 'https://github.com/mohammadazeez963/javaProject.git'
            }
        }
        stage('Compile') {
            steps {
                echo 'Compiling'
            }
        }
         stage('Run') {
            steps {
                echo 'Running'
            }
        }
        
         stage('Test report using jacoco') {
            steps {
                echo 'jacoco'
            }
        }
        
        stage('Building Docker Image') {
            steps {
                echo 'Building Docker Image'
            }
        }
    }
}
