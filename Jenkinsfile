pipeline {
    tools {
jdk "JAVA_HOME"
maven "M2_HOME"
}
agent any
stages {
stage ("git clone") {
steps {
 git "https://github.com/rupali9596/mavcode-1234.git"
}
}
stage ("compile") {
steps {
 sh "mvn compile"
}
}
stage ("package") {
steps {
 sh "mvn package"
}
}
stage ("package") {
steps {
 sh "mvn package"
}
}  
}
}
