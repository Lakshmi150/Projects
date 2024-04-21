Steps:
Here i am creating 2 slave(ubuntu,linux)
 - open AWS console
 - lanch EC2 instance with (ubntu,t2.midum,keypair,storage20)---slave(connect)
 - sudo apt update -y
 - sudo apt upgrade -y
 - curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \
  /usr/share/keyrings/jenkins-keyring.asc > /dev/null
- echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/nul
  - sudo apt-get update -y 
  - sudo apt-get install jenkins -y




