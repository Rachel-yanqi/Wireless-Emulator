**Prerequisites:  Ubuntu 14.04 python2 python-dev**  
1.Update your software and functions  
sudo apt-get update  
sudo apt-get dist-upgrade  
sudo apt-get install bash bridge-utils ebtables iproute libev-dev python tcl8.5 tk8.5 libtk-img  
2.Install QUAGGA-0.99.21mr2.2 with wireless for routing  
https://github.com/USNavalResearchLaboratory/ospf-mdr/releases/download/v0.99.21mr2.2/quagga-mr_0.99.21mr2.2_amd64.deb  
sudo dpkg -i quagga-mr_0.99.21mr2.2_amd64.deb  
3.Install core 4.8 and Build  
git clone https://github.com/coreemu/core.git  
./bootstrap.sh  
./configure  
make  
sudo make install  
