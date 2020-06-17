node {
stage( 'scm checkout') {
git 'https://github.com/javahometech/my-app.git'
}
stage ( 'compile') {
 sh 'mvn clean package'
}
}
