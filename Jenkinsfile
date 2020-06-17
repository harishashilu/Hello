node {
stage( 'scm checkout') {
git 'https://github.com/harishashilu/Hello.git'
}
stage ( 'compile') {
 def mvnhome = tool name: 'maven3', type: 'maven'
 sh "${mvnhome}/bin/mvn compile"
}
}
