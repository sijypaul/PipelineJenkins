pipeline
{
  agent any

  stages 
  {
     stage ('Compile') 
     {
           steps {
                    echo "Compiling......."
                    bat 'javac Hello.java'
                 }
     }
     stage ('Test') 
     {
           steps {
                   echo "Testing......."
                   bat 'java Hello'
                 }
     }
     stage ('Deploy') 
     {
           steps {
                   echo "Deploying......"
                 }
     }
  }
}
