ipipeline {
    agent any
    stages {
        stage('Check Code') {
            steps {
                sh "ls -la"
                echo "📁 Code is present!"
            }
        }
        stage('Build (Compile Check)') {
            steps {
                sh "python3 -m py_compile app.py"
                echo "✅ Build successful - no syntax errors!"
            }
        }
        stage('Run Tests') {
            steps {
                sh "python3 -m unittest test_app.py"
                echo "✅ All tests passed!"
            }
        }
    }
    post {
        always {
            echo "🏁 Pipeline execution finished."
        }
        success {
            echo "🎉 SUCCESS: Everything passed! Great job."
        }
        failure {
            echo "❌ FAILURE: Something broke. Check the logs above."
        }
    }
}
