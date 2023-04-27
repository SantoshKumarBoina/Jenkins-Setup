# Jenkins-Setup
In this I have written all the commands to set-up jenkins server in amazon linux machine



  sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
  sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
  
  amazon-linux-extras install java-openjdk11 -y   [ To install java version 11.8.0]
  
  yum install git maven jenkins -y [ To install packages]
  
  systemctl start jenkins    [ To start the service]
  
  systemctl status jenkins [ To check the status of jenkins servivce]
  
  <Public IP > : 8080
