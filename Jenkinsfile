node{
    def repoUrl = 'https://github.com/ru-baker1/exp4.git'
    def deployDir = "C:\\xampp\\htdocs\\Exp4"
    stage('deploy to xampp server'){
       
        git branch: 'main' , url: repoUrl
        bat "xcopy *.html ${deployDir} /Y"
    }
    
      
    
   
    
}
