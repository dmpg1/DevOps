pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                echo 'Привет! Это мой второй пайплайн!'
            }
        }

        stage('Connecting...') {
            steps {
                echo 'Подключаемся к git репозиторию'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Собираем проект...'
                sh 'echo "Build completed"'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Запускаем тесты...'
                sh 'echo "All tests passed"'
            }
        }
    }
}
