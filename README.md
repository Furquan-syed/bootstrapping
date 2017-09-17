# bootstrapping
#bootstrapping commands

#in configure instance
#go to the advance settings
#and paste the below commands




* #!/bin/bash
  sudo su
  apt-get update -y
  apt install apache2 -y
  service apache2 start
  
  
