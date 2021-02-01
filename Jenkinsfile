pipeline{
    agent any
    options{
        ansiColor('xterm')
    }
    
    stages{
        stage ('Build'){
            steps{
                git url: 'https://github.com/strongloop-community/jenkins-example.git', branch: 'master'
                sh 'yarn'
            }
        }
        stage ('Deployment'){
            steps{
                sh 'Echo "hola nacho"'
            }
        }
    }
}
