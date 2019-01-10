def workspace 
node 
{
    stage ('Checkout')
    {
      checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/talukder9712/SampleProject.git']]])
        workspace =pwd() 
    }
    
    stage ('Static Code Analysis')
    {
    echo "Static Code Analysis"    
    }
    
    stage ('Build')
    {
    echo "Build"    
    }
    
     stage ('unit testing')
    {
    echo "unit testing"    
    }
     stage ('delivery')
    {
    echo "delivery"    
    }
}
