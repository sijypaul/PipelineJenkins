pipeline
{
  agent any

  stages 
  {
     stage ('Compile') 
     {
           steps {
                    echo "Compiling......."
                    javac Hello.java;
                 }
     }
     stage ('Test') 
     {
           steps {
                   echo "Testing......."
                   java Hello;
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
