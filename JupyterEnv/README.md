# Install Your Own Python Environment
This short description will show you, how to set up Your own Python environment with Jupyter notebook and a lot of useful Libraries. During this process, You'll setup a virtual machine so it will work on Windows, MacOS and Linux operating system as well.

## Requirements
* https://www.virtualbox.org/
* https://www.vagrantup.com/
* 5 Gb free space in your Home folder (VirtualBox put all data into a specific folder inside your home folder)
* High speed internet (this process will download more then 1 Gb of data)
* 30-60 minutes, depends of your computer

## Setup
### Step 1
Download and install VirtualBox and Vagrant. Both software are necessary for you can use this environment.

### Step 2
Download this repository https://github.com/fazekasda/MyPythonLeanrPack/archive/master.zip, then compress the zip file. (or clone with git: `git clone https://github.com/fazekasda/MyPythonLeanrPack.git`)

### Step 3
Open a terminal. Enter the folder where You uncompressed the zip file, and enter the MyPythonLeanrPack-master folder and the JupyterEnv folder. (type this command: `cd where_uncompressed_the_zip_file/MyPythonLeanrPack-master/JupyterEnv`)
This folder contains all the configuration file which need to setting up the environment. `Vagrantfile` contains informations about the virtual machine and the configuration workflow. `python2_packages.txt` and `python3_packages.txt` files contains the list of python packages which will installed.

### Step 4
To start the installation process type this command: `vagrant up`
This command tells Vagrant to download a base virtual machine and all the packages what needed and install those on the virtual machine. That could be take 30-60 minutes. After that the virtual machine will start automatically and run in the background.

### Step 5
Open [http://localhost:8888](http://localhost:8888) in your bowser.

## Usage
