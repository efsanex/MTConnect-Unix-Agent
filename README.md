# MTConnect-Unix-Agent
MTConnect Ubuntu Agent


<br/>
sudo add-apt-repository ppa:ubuntu-toolchain-r/test <br/>
sudo apt install gcc-9 g++-9 <br/>
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-9 90 --slave /usr/bin/g++ g++ /usr/bin/g++-9 --slave /usr/bin/gcov gcov /usr/bin/gcov-9 <br/>
<br/>
<br/>
chmod u+x agent<br/>
<br/>
./agent debug
