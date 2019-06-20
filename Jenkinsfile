pipeline {
agent any
stages {
stage('checkout') {
steps {
println "Current branch ${env.BRANCH_NAME}"
}
}
stage('build') {
steps {
bat 'python my_software.py'
}
}
}
}
