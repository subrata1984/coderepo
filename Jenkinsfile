 pipeline {
    agent docker {
       image 'subrata1984/nginx_container' 
       tools {
         maven 'apache-maven-3.0.1'
      }
    }
    stages {
       stage ('Build Hello-World') {
         steps {
            echo "maven install"       
       }
    }  
  }
}
