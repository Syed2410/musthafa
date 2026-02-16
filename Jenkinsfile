pipeline { 
  agent any 
  stages {
    stage ('version') {
       steps {
         bat '"C:\\Users\\Sindhu I\\AppData\\Local\\Python\\bin\\python.exe" --version'
       }
    } 
    stage ('Hello') {
      steps {
        bat '"C:\\Users\\Sindhu I\\AppData\\Local\\Python\\bin\\python.exe" python File1.py'
      }
    }
  }
}

