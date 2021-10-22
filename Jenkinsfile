pipeline {
    agent { label 'maven' }
    stages {
        stage('Clone git repo') {
            steps {
                echo 'first stage'
            }
        }
		
		stage('maven build - package ') {
            steps {
                echo 'second stage'
			}
		}
		
    }
}
