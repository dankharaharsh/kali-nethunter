# kali-nethunter

## this process was applicable on non-rooteble devices.

---

## The main application where you have to run these all cmd's is **TERMUX**.
You have to download TERMUX from play store.

---

after download the first step was to install basic commands which was start from.

#### basic package installtion.
```
pkg update && pkg upgrade -y
pkg install git wget curl -y
termux-setup-storage
```

#### Essential Packages.
```
pkg install python -y
pkg install python2 -y
pkg install nodejs -y
pkg install clang -y
pkg install make -y
pkg install vim nano -y
```

#### Python Setup
```
pip install --upgrade pip
pip install requests
pip install flask
```

#### Networking Tools
```
pkg install nmap -y
pkg install net-tools -y
pkg install dnsutils -y
pkg install tcpdump -y
```

#### Pentesting Environment
```
pkg install openssh -y
pkg install hydra -y
pkg install sqlmap -y
```

#### Kali NetHunter [ If you want to download kali linux into TERNUX so you have to run the below command ]
```
pkg install wget -y
wget -O install-nethunter-termux https://offs.ec/2MceZWr
chmod +x install-nethunter-termux
./install-nethunter-termux
```

Then Run below command.
```
nethunter
```

---

### These are the basic command which was used to run kali linux on android device.
