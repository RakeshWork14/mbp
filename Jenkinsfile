pipeline{
    agent {
        label 'java-label'
    }
    environment{
        name = "Rakesh"
        course = "Devops"
        cloud = "Azure"
    }
    stages{
        stage('Rakesh'){
            steps{
                echo "My name is ${name}, and course is ${course}, and cloud is ${cloud}"
            }
        }
        stage('sai'){
            environment{
                name = "sai"
                course = "React"
                cloud = "AWS"

            }
            steps{
                echo "My name is ${name}, and course is ${course}, and cloud is ${cloud}"
            }
        }
        stage('yash'){
            environment{
                name = "yash"
                course = "Android Development"
                cloud = "GCP"

            }
            steps{
                echo "My name is ${name}, and course is ${course}, and cloud is ${cloud}"
            }
        }
    }
}
