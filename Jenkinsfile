pipeline{
    agent any
    stages{
        stage('version'){
            steps{
                bat '"d:\\Jenkins\\musthafa\\cmd.exe" /d python --version'
            }
        }
        stage('STAGE2'){
            steps{
                bat '"d:\\Jenkins\\musthafa\\cmd.exe" /d python File.py %X_VALUE% %Y_VALUE%'
            }
        }
    }
}