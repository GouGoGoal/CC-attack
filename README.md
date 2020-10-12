       /////    /////    /////////////
      CCCCC/   CCCCC/   | CC-attack |/
     CC/      CC/       |-----------|/ 
     CC/      CC/       |  Layer 7  |/ 
     CC/////  CC/////   | ddos tool |/ 
      CCCCC/   CCCCC/   |___________|/

# CC-attack ![](https://img.shields.io/badge/Version-3.4-brightgreen.svg) ![](https://img.shields.io/badge/license-GPLv2-blue.svg)
 A script for using socks4/5 proxies to attack http server.

 News:
- [x] Added new api for downloading socks
- [x] Removed useless code

 Info:
- [x] Using Python3
- [x] Added more human-like options
- [x] Http Get  Flood
- [x] Http Head Flood
- [x] Http Post Flood
- [x] Http Slow Attack
- [x] Support HTTPS
- [x] Socks4 Proxies Downloader
- [x] Socks4 Proxies Checker
- [x] Socks5 Proxies Downloader
- [x] Socks5 Proxies Checker
- [x] Random Http post data
- [x] Random Http Header
- [x] Random Http Useragent
- [x] Customize Cookies
- [x] Customize post data 
- [x] Added proxies mode selection
- [x] Optimize code
- [x] Fixed low performance
- [x] Added event for concurrent
- [x] Select proxies at start of thread for performance

## Install

    pip3 install requests pysocks
    git clone https://github.com/Leeon123/CC-attack.git
    cd CC-attack

## Usage

    python3 cc.py
    后台运行：安装screen
    创建一个新后台：screen -S cc
    运行脚本：python3 cc.py
    切入后台：Ctrl + a +d 
    恢复前台：screen -r cc
