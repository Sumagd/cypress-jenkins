pipeline{
    agent any
        stages {
            stage('build'){
                steps{
                    sh 'npm install'
                    sh 'npm install cypress@9.5.0'
                    sh 'npx run cypress:run'
                }
            }
        }
    
}





