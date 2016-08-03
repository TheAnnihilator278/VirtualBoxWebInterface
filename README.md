# VirtualBoxWebInterface
Web interface for Oracle VirtualBox

VirtualBox Web Interface was built for Ubuntu server, but should run on any linux system that supports python2.7.X and python-pip

####Requirements: 
  python-pip is installed and upgraded to the latest
  on ubuntu install with: apt-get install python-pip
  
####Installation:
<p>apt-get install python-pip</p>
  pip install pip --upgrade
  git clone https://github.com/DexterOctana/VirtualBoxWebInterface.git
  cd VirtualBoxWebInterface
  python ./install.py
  service virtualboxwebinterface start
  open a browser and go to http://your-server-ip:50
  
  
####Change login username/password:
  edit VirtualBoxWebInterface.py line 37
  Better user managment to come with Version 1.1!

