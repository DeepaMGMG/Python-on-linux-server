# Python-on-linux-server
This repository containscommands to install python and virtual environment in linux server




Commands to install python3 and pip3
=================================
sudo apt-get install python3.7
sudo apt install python3-pip

Commands to install virtual environment 
===================================================
sudo apt install python3-venv

Command to create and activate virtual environment
===============================================
python3 -m venv my_own_venv
cd /path/to/my_own_venv
source my_own_venv/bin/activate

Install required libraries using requirements file
=================================================
pip install -r requirements.txt
