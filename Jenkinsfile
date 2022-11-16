pipeline{
    agent any
    environment{
    PATH = "C:/Users/admin/Documents/apache-maven-3.6.3"
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
        sh "mvn clean package"
        }
    }
}

}
