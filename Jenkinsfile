pipeline
{
  agent any

  stages 
  {
     stage ('Compile') 
     {
           steps {
                   javac Hello.java
                 }
     }
     stage ('Test') 
     {
           steps {
                   java Hello
                 }
     }
     stage ('Deploy') 
     {
           steps {
                   echo "Deploy App"
                 }
     }
  }
}
