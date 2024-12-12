pipeline {
    agent any

    stages {
       stage('terraform plan') {
            steps {
                sh '''
                sudo pwd
                sudo ls
                sudo terraform init
                sudo terraform plan
'''
    }
}
}
}
