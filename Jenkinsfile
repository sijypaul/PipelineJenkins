pipeline
{
  agent any

  stages 
  {
    stage('Build') 
        {
            steps 
            {
               git branch: 'main', url: 'https://github.com/sijypaul/PipelineJenkins.git'
            }
        }
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
