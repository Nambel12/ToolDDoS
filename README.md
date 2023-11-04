# Tool DDoS
A tool ddos can bypass cloudflare,google shield,normal anti ddos,...

# Run On Termux📱,Linux,Window.

# Setup(for termux if install pyroxy and cryptography module failed!)

termux-setup-storage
apt update && apt upgrade -y
apt install python3
apt install rust
apt install git
apt install python-cryptography
git clone https://github.com/NamBel12/ToolDDoS.git
cd ToolDDoS
pip install -r requirements.txt
python3 ddos.py
