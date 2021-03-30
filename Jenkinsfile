pipeline{
    agent any
    stages{
        stage("compiling"){
            steps{
                echo "========Compiling java program========"
                sh 'javac HelloWorld.java'
            }
        }
        stage("executing"){
            steps{
                echo "========executing java program========"
                sh 'java HelloWorld'
            }
        }
    }
}