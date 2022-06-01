pipeline {

agent any

stages {
    stage('Execute Shell') {
                    steps {
                        sh 'java Hello.java'
                    }
                }

stage('Build') {

steps {
git 'https://github.com/tejashrimargam5/Ass5.git'
 sh ('echo "Hello"')
}

}

stage('Run') {

steps {
"""git 'https://github.com/tejashrimargam5/Ass5.git'
"""
  sh ('echo "Hello"')
}
}
 
}
}
