pipeline {
agent any
stages {
stage (checkout) {
steps {
git 'https://github.com/shubhmatre/Mavjen1.git' }
}
stage (compile) {
steps {
sh 'mvn install'
}}
stage (deploy) {
steps {
sh 'cp target/Mavjen1 /home/shubham/Documents/devops/apache-tomcat-9.0.93/webapps'
}}}}
