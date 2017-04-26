repository = 'kafka-docker'

node {

    stage('Checkout') {
        checkout scm
    }

    stage('Test') {
        echo "no tests yet..."
    }

    stage('Build') {
        sh "docker build -t flow-api . && docker tag express extranet.quva.fi:57104/kafka-docker:latest"
        sh "docker push extranet.quva.fi:57104/kafka-docker:latest"
    }

    stage('Deploy') {
        echo "deploy todo..."
    }

    stage('Integration test') {
        echo "it tests missing..."
    }
}
