pipeline {
    agent any
    stages{
        stage('Clone Git'){/*you can also specify git location */
            steps{
                git 'https://github.com/kopparapusaikrishna/JenkinsPipeline.git'
            }
        }
        
        stage('Build Code'){
            steps{
                sh "chmod u+x Prog1.py"
                sh "./Prog1.py"
            }
        }
        
        stage('Test Code'){
            steps{
                sh "chmod u+x Test.py"
                sh "./Test.py"
            }
        }
    }
}
