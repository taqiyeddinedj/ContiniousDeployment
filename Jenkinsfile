#!/usr/bin/env groovy
def gv

pipeline {
    agent any
    stages {
        
        stage ('Deploy to K8S'){
            steps {
                //gv.deploytok8s()
                kubernetesDeploy configs: 'webapp-deployment.yaml',kubeconfigId: 'kubernetes'
                    
                
            }
        }
    }
}