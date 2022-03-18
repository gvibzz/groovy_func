def Greet(name,msg,info) {
    echo "Hello ${name} ${msg}_${info}"
}


pipeline {
    agent any

    stages {
        stage('Function test') {
            steps {
                echo 'Call function..'
                Greet('Technological Death', 'Amiga','RULLEZZ')
            }
        }
    }
}
