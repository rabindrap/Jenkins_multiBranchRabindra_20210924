node('master')
{
    stage('Continuous Download_mstr')
        {
    git 'https://github.com/sunildevops77/maven.git'
        }
    stage('Continuous Build_mstr')
        {
    sh label: '', script: 'mvn package'
        }
}

