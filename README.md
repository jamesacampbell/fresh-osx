# fresh-osx

_a collection of setup scripts &amp; default app installer for a fresh Mac OS install complete with a full & core version_

## HOW TO RUN

Simply run `git clone https://github.com/jamesacampbell/fresh-osx.git` and then `cd fresh-osx` and then `python installer.py` and you are done.

## INCLUDED CORE (lite setup)

[HOMEBREW](https://brew.sh)  
[TUNNELBLICK](https://www.tunnelblick.net/)   
[CHROMIUM](https://www.chromium.org/)  
[ZSH](https://www.zsh.org/) & [OH-MY-ZSH](http://ohmyz.sh/)     
[GPG TOOLS](https://gpgtools.org/)   
[TOR](https://www.torproject.org/download/download.html.en) (brew services start tor, config in /usr/local/etc/tor/, running at 127.0.0.1:9050)     
[PRIVOXY](http://www.privoxy.org/) (brew services start privoxy, config in /usr/local/etc/privoxy/, running at 127.0.0.1:8118)    
[PYTHON 3 & PIP](https://www.python.org/)     
lots of python libraries via requirements.txt   
LOCK DOWN FIREWALL   
TURN ON FULL DISK ENCRYPTION   
DUMP FULL DISK ENCRYPTION KEY OUT OF MEMORY ON SLEEP    

## INCLUDED BATTERIES INCLUDED

ALL OF CORE PLUS:   
[TASKWARRIOR](https://taskwarrior.org/)          
[IMAGEMAGICK](https://www.imagemagick.org/script/index.php)         
[ETCHER](https://etcher.io/)   
[BARTENDER](https://www.macbartender.com)   
[CODA](https://www.panic.com/coda/)
[PHP-FPM](https://php-fpm.org/download/)      
[NGINX](https://nginx.org/en/download.html)   
[MYSQL](https://dev.mysql.com/downloads/)   
[NODE](https://nodejs.org/en/download/) / [NPM](https://www.npmjs.com/package/download)         
[HTOP](http://hisham.hm/htop/)   
[TMUX](https://github.com/tmux/tmux/wiki)   

## HOW TO CONTRIBUTE

Fork it and issue a pull request!

## FUTURE PLANS

(DONE but needs tested) Adding a lite option that doesn't include php-fpm nginx mysql etcher taskwarrior node npm python3 pip htop tmux
Adding an ansible version instead of pure BASH.
