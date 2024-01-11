#!/usr/bin/env groovy
def gv

pipeline {
    agent any
    stages {
        
        stage ('Deploy to K8S'){
            steps {
                //gv.deploytok8s()
                sh 'kubectl apply -f webapp-deployment.yaml'
                    
                
            }
        }
    }
}