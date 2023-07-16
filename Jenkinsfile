pipeline
{
    agent any
    stages
    {
        stage("checkout_code")
        {
            steps
            {
                git 'https://github.com/nocturnaldevops/TridentGlobal.git'
            }
        }
        stage("build")
        {
steps{


            sh 'clean sonar:sonar package'
}
        }
    }
}
