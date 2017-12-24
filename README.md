# <p align="center"><b> MONITORR </b></p>

<p align="center"><b>Webfront to live display the status of any webapp or service  </b></p>
<br>

<b> Version:</b> v0.11.0d [BETA]

[![](https://img.shields.io/github/release/monitorr/monitorr.svg?style=flat)](https://github.com/monitorr/monitorr/releases)

[![Docker build](https://img.shields.io/docker/build/monitorr/monitorr.svg?maxAge=2592000)](https://hub.docker.com/r/monitorr/monitorr/)

<b> Latest major change: </b> Added index.min.php for optimal display when using as iframe plug-in (See [WIKI](https://github.com/Monitorr/Monitorr/wiki/Integration:--Organizr))

## Features:

- LIVE!
- Self-hosted
- Monitor any app on any domain
- Host system resources display (CPU, MEM, PING, Uptime)
- Server DTG data
- Update Monitorr via web UI / branch switching
- Minimal UI for iFrame displays (See [WIKI](https://github.com/Monitorr/Monitorr/wiki/Integration:--Organizr))
- User customizable system threshold colors

<b> Features in development: </b>
- UL/DL times via Speedtest
- Settings page
- Drag 'n drop tiles


## Screenshot :

<img src="https://i.imgur.com/6fn9mMc.png[/img]">

<br>

In use with [Organizr](https://github.com/causefx/Organizr)

<img src="https://i.imgur.com/7vAZJbS.png[/img]">


## Prerequisites:
1) [PHP](https://secure.php.net/downloads.php)

2) [PHP cURL](https://secure.php.net/manual/en/book.curl.php)

<br>

## Configuration:
1) Clone/download repository to your webserver (Suggested Sub DIR)

2) Make sure the user account that runs your webserver has RW access to the monitorr folder (eg. for linux it's usually www-data:www-data) - this is for updates to work properly.

3) Browse to <localhost\domain>/monitorr/index.php (config.php will be auto populated in /assets/config.php)

4) Edit `assets/config.php`:
 - timezone
 - Site Title
 - Site URL
 - Ping address
 - Sys info color thresholds
 - Services you want to monitor
 - Branch you want to be on for updates (master/develop)

5) Enjoy! Have a Donut. Drink a Coffee.
<br>

## Feature Requests:
 [![Feature Requests](https://cloud.githubusercontent.com/assets/390379/10127973/045b3a96-6560-11e5-9b20-31a2032956b2.png)](https://feathub.com/Monitorr/Monitorr)

<b> Current feature requests: </b>

[![Feature Requests](https://feathub.com/Monitorr/Monitorr?format=svg)](https://feathub.com/Monitorr/Monitorr)
<br>

## Connect:
Need live help?  Join here :   [![Discord](https://img.shields.io/discord/102860784329052160.svg)](https://discord.gg/YKbRXtt)
<br>
E-mail: monitorrapp@gmail.com
<br>
Buy us a beer! Donate:        [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/monitorrapp)

## About Us:
- [seanvree](https://github.com/seanvree) (Windows Wizard)
- [jonfinley](https://github.com/jonfinley) (Linux Dude)
- [wjbeckett](https://github.com/wjbeckett)
