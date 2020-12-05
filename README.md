# Puffin Browser on Linux - Unofficial instructions about installing Puffin Internet Terminal on Linux
_Note: for **Windows** the browser is called **Puffin Secure Browser** or simply **Puffin Browser**, for **Linux** the browser is called **Puffin Internet Terminal**. Initially **Puffin Internet Terminal** is intended for **Raspberry Pi** devices, but this does not prevent it from being installed on a regular Debian-based computer.
You can still use the Chromium or Firefox browsers but the performance is barely acceptable on Raspberry Pi, or if you have a very low Internet speed._

**Puffin Internet Terminal** is a functional browser with support for modern technologies. The main feature of the program is support for Adobe Flash technology for viewing video, multimedia elements or a full version of websites. Puffin Internet Terminal provides fast page loading with **cloud-based content compression technology** and **saves traffic**. The program allows anonymous use of the browser, does not save the history of viewed websites. Puffin Internet Terminal also **encrypts traffic** to protect against external influences and **supports working with cloud storage**.

**Benefits**:
- Support for Adobe Flash technology (not particularly relevant).
- Сloud-based content compression technology with saving and encrypts traffic.
- Supports working with cloud storage.
- Pretty cheap price, just $2 a month, for the first month for free, for such a browser is not sorry to pay so much

**Disadvantages**:
- Based on old version of Chromium engine, because of this, some sites refuse to working.
- No support for DRM and browser extensions

## Installation :
### For Debian-based systems (armhf, i386, x86_64) :
```
sudo apt update && sudo apt install wget -y && wget -q  -O- | sudo apt-key add - && sudo wget https://raw.githubusercontent.com/ZhymabekRoman/Puffin-Browser-on-Linux/main/puffin-internet-terminal.list -O /etc/apt/sources.list.d/puffin-internet-terminal.list
```
