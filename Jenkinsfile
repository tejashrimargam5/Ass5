pipeline {

agent any

stages {

stage('Build') {

steps {
git 'https://github.com/tejashrimargam5/Ass5.git'
 sh ("javac Hello.java")
}

}

stage('Run') {

steps {
git 'https://github.com/tejashrimargam5/Ass5.git'
sh ("java Hello")
}
}
}
}
