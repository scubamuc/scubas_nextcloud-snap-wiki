
---

# Nextcloud-snap & LXD

## Lenovo ThinkCentre M92p Tiny

### Ubuntu 20.04

#### **Hardware**:

```
Lenovo ThinkCentre M92p Tiny
+ Bauform: SFF
+ Prozessor: Intel Core i5-4570T 
  (2x 2,9+ GHz / 4 MB Cache / 64-bit / 35 Watt)
+ Prozessorgrafik: Intel HD 4600
+ inst. Speicher: 10GB DDR3 (1x8GB+1x2GB)
+ 1. Festplatte: 500GB Solid State Disk
+ Netzteil: 65 Watt extern
```

**Nextcloud-snap**: nextcloud

---

# Hardware -- persönliche Nextcloud

Eine persönliche Nextcloud lässt sich hervorragend auf einem ressourcenschonenden SBC wie **Raspberry Pi** betreiben.

Je nach Strom-Anschlussmöglichkeit sind Bsp. **Raspberry Pi 3B** oder **Raspberry Pi 2B** sehr gut geeignet, wobei ein **Raspberry Pi 3B** einen leistungsfähigeren Prozessor und mehr Arbeitsspeicher zur Verfügung stellt und somit flüssigeres Arbeiten ermöglicht.

Allerdings verlangt ein **Raspberry Pi 3B** eine eigene Stromversorgung. Zum Vergleich könnte der **Raspberry 2B** direkt über den USB-Anschluss des Routers gespeist werden.

## Alternative Hardware

**Raspberry Pi 3B:**

```
  Beschreibung: ARMv7 Processor rev 4 (v7l)
  Produkt: Raspberry Pi 3 Model B Rev 1.2
  Seriennummer: 00000000bfe04906
  Breite: 32 bits
  Fähigkeiten: smp
  
    *-network
 		Beschreibung: Ethernet interface
 		Physische ID: 2
 		Logischer Name: enxb827ebe04906
 		Seriennummer: b8:27:eb:e0:49:06
 		Größe: 100Mbit/s
 		Kapazität: 100Mbit/s
 		Fähigkeiten: ethernet physical tp mii 10bt 10bt-fd 100bt 100bt-fd autonegotiation
 		Konfiguration: autonegotiation=on 
 		broadcast=yes driver=smsc95xx
 		driverversion=22-Aug-2005 duplex=full 
 		firmware=smsc95xx USB 2.0 
 		Ethernet ip=192.168.2.36 
 		link=yes multicast=yes port=MII speed=100Mbit/s
```

* Set komplett: **[Raspberry Pi 3B](https://www.amazon.de/gp/product/B01MYQXBE1/ref=ppx_yo_dt_b_search_asin_image?ie=UTF8&psc=1)**
* Stromversorgung: [Original Raspberry Pi 3B Stromversorgung](https://www.amazon.de/gp/product/B01M58O9M9/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
* Gehäuse: [Orbital Case ](https://www.polypodis.de/produkte/)weiß
* Temparatur: [CPU + GPU Kühlkörper](https://www.amazon.de/Aukru-K%C3%BChlk%C3%B6rper-verschiedenen-Raspberry-Aufkleben/dp/B00ILK6DMA/ref=pd_sbs_147_7?_encoding=UTF8&pd_rd_i=B00ILK6DMA&pd_rd_r=1dc5deb6-9ac4-4e1f-b3d9-3f82591779c2&pd_rd_w=vlKiE&pd_rd_wg=494Qz&pf_rd_p=c8718c55-fb13-473f-a41c-592a17ad3468&pf_rd_r=QS66H0Y836TNTBQKHKZY&psc=1&refRID=QS66H0Y836TNTBQKHKZY) (Aluminium)
* **2x** SDHC-Karte: **SanDisk Ultra 128GB** oder **SanDisk Ultra 64GB** Micro Class10

---

### Software

* Ubuntu LTS 
* Nextcloud-Snap
* SSH/SFTP (nur Lokal) kein externer Zugriff!
* SSL-Verschlüsselung über LetsEncrypt (Nextcloud-snap)
