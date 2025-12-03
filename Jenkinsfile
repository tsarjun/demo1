ipeline { 
agent any 
stages {
    stage ('clone project'){
        steps {
            git branch:'master',url:'https://github.com/tsarjun/demo1.git'
    }
}
stage('clean'){
    steps{
        sh 'mvn clean'
    }
}
stage('compile'){
    steps{
        sh 'mvn complie'
    }
}
stage('test'){
    steps{
        sh 'mvn test'
    }
}
stage('build'){
    steps{
        sh 'mvn clean install'
    }
}
}
}
