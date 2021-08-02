pipeline {
    agent any
    stages {
        stage ('greeting') {
            steps {
                script {
                    println "Good Mrng ${Name}!!"
                }
            }
        }
        stage ('Name') {
            steps {
                script {
                    println "Name of the user: ${name}"
                }
            }
        }
        stage ('Location') {
            steps {
                script {
                    println "Name of the location: ${Loc}"
                }
            }
        }
    }
}
