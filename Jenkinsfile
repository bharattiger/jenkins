pipeline {
    agent any
    parameters {
        string(name: 'servicename', defaultValue: 'windows update', description: 'stop')}
}
stages {
        stage('paratest1') {
            steps {
                powershell "New-Item -ItemType file -path c:\tigerbharat"
            }
        }
    }
}
