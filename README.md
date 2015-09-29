# steamos-xpad-dkms
Valve patched xpad driver

# Purpose
Rebuild patch xpad driver to maintain a fresh up to date package for non-SteamOS users.
	 
To build manually:
======================

cd source/
mkdir build
cd build
cmake ..
make
sudo make install

# Source
https://github.com/ValveSoftware/steamos_kernel
