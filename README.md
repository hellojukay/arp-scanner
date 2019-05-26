# arp-scanner
scan local area network ip and mac address

[![Build Status](https://travis-ci.org/hellojukay/arp-scanner.svg?branch=master)](https://travis-ci.org/hellojukay/arp-scanner)
## Install
```shell
go get -u github.com/hellojukay/arp-scanner
```
## Usage
```shell
± |master ✓| → sudo arp-scanner -iface enp30s0                                    
192.168.199.1       d4:ee:07:52:b9:7a
192.168.199.177     a4:50:46:37:95:b9
192.168.199.1       d4:ee:07:52:b9:7a
192.168.199.1       d4:ee:07:52:b9:7a
192.168.199.1       d4:ee:07:52:b9:7a                                            
```
