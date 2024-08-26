pipeline {
agent any
stages {
stage (checkout) {
step {
git 'https://github.com/shubhmatre/Mavjen1.git' }
}
stage (compile) {
step {
sh 'mvn install'
}}
stage (deploy) {
step {
sh 'cp target/Mavjen1 /home/shubham/Documents/devops/apache-tomcat-9.0.93/webapps'
}}}}
