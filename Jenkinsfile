node {
  try {
    stage('Checkout') {
      checkout scm
    }
    stage('Environment') {
      bat 'git --version'
      echo "Branch: ${env.BRANCH_NAME}"
     
     
    }
    stage('Build Docker test'){
      echo "Branch: ${env.BRANCH_NAME}"
    }
    stage('Docker test'){
      echo "Branch: ${env.BRANCH_NAME}"
    }
    
    }
  }
  catch (err) {
    throw err
  }
}
