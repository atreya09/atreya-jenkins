# atreya-jenkins


INSTALLATION:

install java (if this comnd not works try visiting offcial installation on jenkins page https://www.jenkins.io/doc/book/installing/linux/)
sudo apt-get -y install openjdk-11-jdk

wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -
sudo sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'


now do upgrade cos many time simply doing update wont help
sudo apt upgrade


then do this
sudo apt update
sudo apt-get install jenkins -y

cat /var/lib/jenkins/secrets/initialAdminPassword -- get the pwd and then run localhost?:8080 on browser
