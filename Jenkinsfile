pipeline {
    
    agent any
    
    stages {
        stage('Submodule Sync') {
            steps {
                sh 'git submodule sync'
                sh 'git submodule update --init --recursive'
            }
        }
        stage('Clean Workspace') {
            steps {
                echo "cleaning workspace"
            }
        }
        stage('Lint YAML files') {
            steps {
                echo "linting yaml"
            }
        }
        stage('Build EO Helm Chart Validator Testsuite Image') {
            steps {
                echo "executing helm chart validator"
            }
        }
        stage('Run EO Helm Chart Validator Testsuite') {
            steps {
                echo "running eo validator"
            }
                                                        }
           }
}
