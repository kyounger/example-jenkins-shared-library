@Library('custom-global-shared-library') _

pipeline {
    agent any
    stages {
        stage('custom-step') {
            steps {
                customStep()
            }
        }
        stage('custom-step-with-arg') {
            steps {
                customStepWithArg(param1: 'customStepValue')
            }
        }
    }
}
