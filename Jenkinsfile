def Greet(name) {
    echo "Hello ${name}"
}





pipeline {
    agent any

    stages {
        stage('Function test') {
            steps {
                echo 'Call function..'
                Greet('Technological Death')
            }
        }
    }
}
