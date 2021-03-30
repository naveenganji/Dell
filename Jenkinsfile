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
                echo "testing webhook changes"
                sh 'java HelloWorld'
            }
        }
    }
}
