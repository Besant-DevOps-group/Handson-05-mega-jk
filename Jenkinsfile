pipeline{
    agent any
    stages{
        stage('print name'){
            steps{
                echo"mega"
            }
        }
        stage('test'){
            steps{
                sh "python3 ./main_test.py"
            }
        }
    }
}