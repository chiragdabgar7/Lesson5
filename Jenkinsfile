node('master'){
    stage("Fetch source code"){
        git 'https://github.com/chiragdabgar7/Lesson5'
    }
    dir('Lesson5'){
        printMessage('Running Pipeline')
        
        stage('Testing'){
            sh 'python test_function.py'
        }
        
        printMessage('Pipeline completed')
    }
}
