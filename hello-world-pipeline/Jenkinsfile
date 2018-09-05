 pipeline {
    agent {
       docker { image 'subrata1984/nginx_container' }.withCredentials {credential-id}
       tools {
         maven 'apache-maven-3.0.1'
      }
    }
    stages {
       stage (Build Hello-World) {
         steps {
            echo "maven install"
            mvn --version
           }
       }
 }  
             
