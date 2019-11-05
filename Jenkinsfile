pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
              sh 'echo "Testfile" > test.txt'
              }
        }
        stage('Test'){
            steps{
                sh 'cat test.txt'
            }
        }
        stage('Delete'){
            steps{
                sh 'rm test.txt'
                
            }
        }
    }
}
