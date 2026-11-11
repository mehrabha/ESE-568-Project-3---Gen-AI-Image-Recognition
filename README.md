cd project dir
wsl --install -d Ubuntu
wsl -d Ubuntu
sudo apt update
sudo apt install python3 python3-pip python3-venv
python3 -m venv .venv
source .venv/bin/activate
