pipeline{
    agent any
    stages{
        stage("A"){
            steps{
                echo "========executing A========"
                sh 'ls -l'
                sh 'ansible --version'
                sh 'ansible-inventory --graph'
            }

        }
    }

}