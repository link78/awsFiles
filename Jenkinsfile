pipeline {
    agent any
    parameters{
        string(name: 'Greetings', defaultValue: 'Hello Jenkins community', description:'Just new here'),
        string(name: 'jenkins', defaultValue: 'Refreshing my skills with jenkins'.description: 'most popular build server')
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('Experimenting jenking'){
            steps{
                echo 'Ready to nail the interview'
            }
        }
        stage('using parameters'){
            steps{
                echo "${params.Greetings} in the world"
            }
        }
    }
}
