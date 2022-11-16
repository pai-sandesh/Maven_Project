pipeline{
    agent any
    tools{
        maven '3.8.1'
    }
  
    stages{
        stage("Stage 001"){
            steps{
                echo "hey This is my first demo of pipeline"
            }
        }
        stage("Git Build"){
            steps{
                echo "code pulled from git"
            }
        }
        stage("Maven Build"){
        steps{
            sh 'mvn -version'
        sh 'mvn clean package'
        }
    }
}

}
