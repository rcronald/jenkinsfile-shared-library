@Library('jenkins-shared-library@master')
import customlib.JenkinsLibrary

def customLibrary = new JenkinsLibrary(steps, this)

try{
    node {
        stage('Build'){
            echo "build"
            //customLibrary.steps.echo "Build"
        }
        stage('Test'){
            echo "test"
            //customLibrary.steps.echo "Test"
        }
    }
} catch(Exception e) {
    //customLibrary.steps.echo "ERROR"
    throw e
}