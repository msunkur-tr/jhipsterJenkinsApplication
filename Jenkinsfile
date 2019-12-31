node {
    stage('Build') {
        echo 'Building....'
        withMaven(){ 
            echo 'Building....mvn help:effective-settings'
            mvn help:effective-settings
        }
    }
    stage('Test') {
        echo 'Building....'
        
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}
