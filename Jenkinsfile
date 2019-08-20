@Library('jenkins-shared-library')
import customlib.JenkinsLibrary

def customLibrary = new JenkinsLibrary(steps, this)

try{
    node {
        stage('Build'){  
            customLibrary.steps.echo "Build"
        }
        stage('Test'){  
            customLibrary.steps.echo "Test"
        }
    }
} catch(Exception e) {
    customLibrary.steps.echo "ERROR"
    throw e
}