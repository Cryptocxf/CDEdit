# CDEdit: A Highly Applicable Redactable Blockchain with Controllable Editing Privilege and Diversified Editing Types
We use python and the charm framework to implement a highly applicable redactable blockchain (CDEdit), which has controlled editing privileges and supports multi-edit types.

# Development environment setup for manual configuration
### install dependencies

sudo apt-get update
sudo apt-get install M4
sudo apt-get install flex
sudo apt-get install bison
sudo apt-get install libssl1.0-dev

### install Python3

sudo apt-get install python3
sudo apt-get install python3-setuptools python3-dev

### install gcc

sudo apt install build-essential
sudo apt-get install manpages-dev

### install GMP

sudo apt-get install lzip
wget https://gmplib.org/download/gmp/gmp-6.1.2.tar.lz
lzip -d gmp-6.1.2.tar.lz
tar -xvf gmp-6.1.2.tar
cd gmp-6.1.2
./configure
make
make check
sudo make install

### install PBC

wget https://crypto.stanford.edu/pbc/files/pbc-0.5.14.tar.gz
tar -xvf pbc-0.5.14.tar.gz
cd pbc-0.5.14
./configure
make
sudo make install

### install pip3

sudo apt install python3-pip

### install Charm-Crypto

pip3 install charm-crypto
