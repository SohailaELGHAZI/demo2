node {
  stage("Clone the project") {
    git branch: 'master', url: 'https://github.com/SohailaELGHAZI/demo2.git'
  }

  stage("Compilation") {
    sh "echo 'hii' "
  }

  stage("Tests and Deployment") {
    stage("Runing unit tests") {
      sh "echo 'hello'"
    }
    stage("Deployment") {
      sh "echo 'bonjour'"
    }
  }
}