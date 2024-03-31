<div align=center>
 
 # KRAKEN DDoS
</p>
 DDoS Script with Multiple Bypass<br>( Cloudflare UAM,BFM,NOSEC / etc.. )<br/><br/>
 Don't attack Russian Government sites and .ru domains<br>
 Don't attack any websites you don't own it<br/>
 This was created for educational purposes<br/>
 All responsibilities and disadvantages of using this program is for the user.
 

## Language</br>

 <img src="https://img.shields.io/badge/Python-FFDD00?style=for-the-badge&logo=python&logoColor=blue"/></br>
</div>

# :computer: Main window
<p align="center">
  <img src="https://i.imgur.com/h72OZpu.jpeg">
</p>


# :satellite: Methods:

```sh
  [Layer 7]
 - bypass  | Bypass CF attack
 - flood   | HTTP Flood Attack 
 - httpx   | HTTP 2.0 Request Attack 
 - spoof   | Spoof Attasck
 - get     | Get  Request Attack
 - post    | Post Request Attack
 - head    | Head Request Attack
 - soc     | Socket Attack
 
  [Layer 4]
 - udp     | UDP Flood Attack
 - tcp     | TCP Flood Attack
  
  [Tools]
 - Dns     | Classic DNS Lookup
 - Geoip   | Geo IP Address Lookup
 - Subnet  | Subnet IP Address Lookup
```


# :gift: Installation:
* Linux:
  * `sudo apt update`
  * `sudo apt install python3 python3-pip git -y`
  * `git clone https://github.com/ServerKillers/Kraken`
  * `cd Kraken/`
  * `pip3 install -r requirements.txt`
  * `python3 main.py`

* Termux:
  * `pkg update`
  * `pkg install python3 python3-pip git -y`
  * `git clone https://github.com/ServerKillers/Kraken`
  * `cd Kraken/`
  * `pip3 install -r requirements.txt`
  * `python3 main.py`

# :rocket: Example: HTTP Flood Attack:
```python3 main.py flood https://example.com/ 1000 1000```
<p align="center">
  <img src="https://i.imgur.com/XJztNu9.png">
</p>
