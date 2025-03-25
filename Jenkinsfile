pipeline {
    agent any  // Executa em qualquer agente disponível
    triggers {
        githubPush()  // Isso dispara a pipeline ao receber um push do GitHub
    }
    stages {
        stage('Test') {
            steps {
                echo 'Este é um teste simples'
            }
        }
    }
}
