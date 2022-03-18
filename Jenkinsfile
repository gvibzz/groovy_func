def Greet(name,msg) {
    echo "Hello ${name} ${msg}"
}





pipeline {
    agent any

    stages {
        stage('Function test') {
            steps {
                echo 'Call function..'
                Greet('Technological Death', 'Amiga')
            }
        }
    }
}
