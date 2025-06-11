pipeline {
    tools {
jdk 'JAVA_HOME'
maven 'M2_HOME'
}
agent any
stages {
stage ("checkout") {
steps {
 git 'https://github.com/rupali9596/mavcode-1234.git'
}
}
stage ("compile") {
steps {
 sh 'mvn compile'
}
}
stage ("test") {
steps {
 sh 'mvn test'
}
}      
stage ("package") {
steps {
 sh 'mvn package'
}
}
   stage ("deploy") {
steps {
 sh 'mvn deploy'
}
} 
}
}
