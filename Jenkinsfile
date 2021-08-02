node {
    def name = Name
    def loc = Loc
    stage('Greeting') {
        println "Good Mrng ${name}"
    }
    parallel 'name': {
        stage('Display name') {
            sh "echo $name"
            println "This content is from groovy: ${name}"
        }
    }, 'age': {
        stage('Display location') {
            println "My location is: ${loc}"
        }
    }
}
