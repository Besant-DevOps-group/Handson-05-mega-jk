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
                sh "python ./main_test.py"
            }
        }
    }
}