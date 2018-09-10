 pipeline {
    agent {
       docker { image 'subrata1984/nginx_container' }
    }
    stages {
       stage ('Build Hello-World') {
         steps {
            echo "Hello World"       
       }
    }  
  }
}
