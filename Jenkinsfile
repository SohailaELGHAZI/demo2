node {
  stage("Clone the project") {
    git branch: 'master', url: 'https://github.com/SohailaELGHAZI/demo2.git'
  }

  stage("Compilation") {
    sh "hii"
  }

  stage("Tests and Deployment") {
    stage("Runing unit tests") {
      sh "hello"
    }
    stage("Deployment") {
      sh 'bonjour'
    }
  }
}