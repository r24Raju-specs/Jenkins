jenkins exp

sudo apt update
mkdir -p ~/jenkins && cd ~/jenkins
wget https://get.jenkins.io/war-stable/latest/jenkins.war
sudo apt install -y openjdk-21-jre git
java -version
cd /mnt/c/Users/kanva/Downloads
java -jar jenkins.war --httpPort=8080
cd ~/jenkins
java -jar jenkins.war --httpPort=8080
cat ~/.jenkins/secrets/initialAdminPassword
