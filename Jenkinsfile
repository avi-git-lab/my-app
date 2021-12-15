node{
    stage('SCM Checkout'){
        git 'https://github.com/avi-git-lab/my-app'
    }
    stage('Compile-Package'){
        sh 'mvn package'
    }
}
