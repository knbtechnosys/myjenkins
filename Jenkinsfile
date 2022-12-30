node{
  
    stage('Clone java project') {
   git branch: 'main', url: 'https://github.com/knbtechnosys/DevOps_7PM_Batch.git'
}

stage('Build maven target') {
    sh 'mvn install'
}
    
    
    
}
