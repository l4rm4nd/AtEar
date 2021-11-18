<img src="https://raw.githubusercontent.com/NORMA-Inc/AtEar/master/product_img/atearlogo.png" align="Center">

AtEar is a scalable and efficient system, and also the first web-based wireless vulnerability assessment solution. <br>
This Wireless Vulnerability Analysis/Management Solution, AtEar, can be utilized both by businesses and in the home.  <br>
For business use, AtEar utilizes fingerprint devices for access to the  network and to analyze the current wireless network conditions. <br>The automatic penetration testing function makes it possible to analyze wireless vulnerability conveniently and meticulously. <br>AtEar for home networks inspects network security conditions and monitors for any unregistered devices.

<img src="https://raw.githubusercontent.com/l4rm4nd/AtEar/master/flask_webapp.png" align="Center">

### Operation Video
<a href="https://www.youtube.com/embed/qkqEirRf88E"> Operation Video Link</a>

### AtEar Features
1. Wireless Scanning(Ad-Hoc, Station, Access Point, Soft-Acess Point)
2. Wireless Chart(Channel, Encryption, Type)
3. Wireless Pentesting(WEP, WPA1, WPA2)
4. Network Information Getting(IP, Connected Host Info)
5. Fake AP
    - Google Phishing Sites
    - Facebook Phishing Sites
    - Twitter Phishing Sites
6. WIDS(Wireless intrusion detection system)
    - Disassocation Flood
    - Deauth Flood
    - WESSID-NG Attack
    - Koreck Chopchop attack
    - Fragmentation PGRA Attack
    - MDK MICHEAL SHUTDOWN Exploitation TKIP Attack
    - Attack By TKIPUN-NG
    - Authentication DOS Attack
    - Assocation Flood
    - High Amount of Assocation Sent
    - Suspect Rouge AP
    - Detected Beacon Flood

### Most recommended USB Lancards
***It will aircrack-ng supoorted USB-Lancard***<br>
`asus WL-167g v2`<br>
`Airlink AWLL3026`<br>
`Alfa AWUS036E`<br>
`Alfa AWUS036G`<br>
`Alfa AWUS036S`<br>
`Alfa AWUS050NH`<br>
`Digitus DN-7003GS`<br>
`D-Link DWL-G122 B1`<br>
`D-Link DWL-G122 C1`<br>
`D-Link WUA-1340`<br>
`Edimax EW-7318USg`<br>
`Hawking HWUG1`<br>
`Linksys WUSB54G v4`<br>
`Linksys WUSB54GC v1`<br>
`Linksys WUSB54GC v2`<br>
`Netgear WG111 v1`<br>
`Netgear WG111 v2`<br>
`Netgear WG111 v3`<br>
`Netgear WNDA3100 v1`<br>
`TP-Link TL-WN321G`<br>
`TP-Link TL-WN321G v4`<br>
`Trendnet TEW-429UB C1`<br>
`ZyXEL AG-225H`<br>
`ZyXEL G-202`<br>

### Dependency Programs
`aircrack-ng`<br>
`tshark`<br>
`hostapd`<br>
`python-dev`<br>
`python-flask`<br>
`python-paramiko`<br>
`python-psycopg2`<br>
`python-pyodbc`<br>
`python-sqlite`<br>
`python-pip`<br>

### AtEar Installation Instructions

Clone a copy of the main AtEar git repo by running:
````
cd /opt/
git clone https://github.com/NORMA-Inc/AtEar
cd AtEar 
````
Install python dependencies:
````
virtualnenv -p python2.7 venv # create a virtual env for deprecated python2.7
source venv/bin/activate # activate the virtual env
python install -r requirements.txt # install recommended requirements
````

### How to Run
````
cd /opt/AtEar/
python run.py --iface <interface>
````
This will spawn the AtEar web application on TCP port 0.0.0.0:8080.

