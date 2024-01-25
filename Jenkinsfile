pipeline {
    agent any // This specifies that the pipeline can run on any available agent

    stages {
        stage('Build') { // First stage: Build
            steps {
                echo 'Building the application...'
                // Add your build commands here, such as compiling code, running tests, etc.
            }
        }
        
        stage('Test') { // Second stage: Test
            steps {
                echo 'Running tests...'
                // Add commands to run your tests here
            }
        }
        
        stage('Deploy') { // Third stage: Deploy
            steps {
                echo 'Deploying the application...'
                // Add commands to deploy your application here, such as copying files to a server, etc.
            }
        }
    }
    
    post { // Post-build actions
        success {
            echo 'The pipeline has completed successfully!'
            // Add any actions you want to perform on successful builds
        }
        failure {
            echo 'The pipeline has failed!'
            // Add any actions you want to perform 
