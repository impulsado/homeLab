# homeLab
<img width="40" src="https://user-images.githubusercontent.com/72570835/160851125-da20806b-a367-4e2c-8253-bdd620191ac5.jpg"/> CREATE BY [**impulsado**](https://www.instagram.com/impulsado/)

<br/>

This project aims to use a Raspberry Pi to host **Security** and **Privacy** related services.
<br/>
I could have purchased these same services from outside companies, but I don't trust them to be transparent.
![Photo](https://raw.githubusercontent.com/impulsado/impulsado.github.io/main/assets/img/Photos/Snipaste_2022-09-09_10-54-10.png)

<br/>

## Documentation
In this [website](https://notes.impulsado.org/posts/HomeLab_Project/) you can find the Documentation to Set-up your own Raspberry Pi server.

<br/>

## Overview
### Requirements
| Name | Link | Price |
| --- | --- | --- |
| Raspberry Pi 400  | [Link](https://www.raspberrypi.com/products/raspberry-pi-400/) | 80€ |
| 32 GB MicroSD | [Link](https://www.amazon.es/Gigastone-gs-2in1600-tarjeta-memoria-adaptador/dp/B01N7DE9VG/ref=sr_1_3_sspa?keywords=32gb+micro+sd&qid=1661711836&sprefix=32gb+mi%2Caps%2C133&sr=8-3-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyMFRQMFY0VTVZT1JFJmVuY3J5cHRlZElkPUEwMjAwNzk0VjlTN0lYWVBZWDBCJmVuY3J5cHRlZEFkSWQ9QTAzMzA1NDkxVklRV1JPQkg0MUFNJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==) | 12€ |
| 1 TB HDD | [Link](https://www.amazon.es/WD-Elements-Disco-Externo-port%C3%A1til/dp/B06VVS7S94/ref=sr_1_omk_6?keywords=disco+duro+1tb&qid=1661715026&sr=8-6)| 50€ |
| Domain Name | [Link](https://www.ionos.es/?ac=OM.WE.WEo41K356260T7073a&itc=TOIP6F1L--&utm_source=google&utm_medium=cpc&utm_campaign=SBT-ES-BRA-MIXX---IONOS---&utm_term=ionos&matchtype=e&utm_content=EX-Ionos&gclid=Cj0KCQjw39uYBhCLARIsAD_SzMT1X0HHJYScC4AfSlmHET4NIxGrpzPRqKDf4tvjxGi_lV4szTE8EMoaAga6EALw_wcB&gclsrc=aw.ds) | 10€ |
| Cloudfare | [Link](https://www.cloudflare.com/) | Free |

### Services
#### System
| Icon | Service | Description |
| --- | --- | --- |
| <img src="https://developer.asustor.com/uploadIcons/0020_999_1595573028_AdGuardhome_256.png" width="30" /> | [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) | AdGuard Home is a network-wide software for blocking ads & tracking. |
| <img src="https://raw.githubusercontent.com/pi-hosted/pi-hosted/master/images/wireguard.png" width="30" /> | [PiVPN](https://github.com/pivpn/pivpn) | The Simplest VPN installer, designed for Raspberry Pi. Allow OpenVPN and WireGuard. |

#### Docker
| Icon | Service | Description |
| --- | --- | --- |
| <img src="https://raw.githubusercontent.com/pi-hosted/pi-hosted/master/images/cloudflare-ddns.png" width="30" /> | [Cloudfare DDNS](https://github.com/timothymiller/cloudflare-ddns) | Small and fast DDNS updater for Cloudflare. |
| <img src="https://raw.githubusercontent.com/pi-hosted/pi-hosted/master/images/dashy.png" width="30" /> | [Dashy](https://github.com/Lissy93/dashy) | Dashy helps you organize your self-hosted services by making them accessible from a single place. |
| <img src="https://raw.githubusercontent.com/pi-hosted/pi-hosted/master/images/samba.png" width="30" /> | [Samba](https://hub.docker.com/r/dperson/samba) | Samba has provided secure, stable and fast file and print services for all clients using the SMB/CIFS protocol, such as all versions of DOS and Windows, OS/2, Linux and many others. |
| <img src="https://raw.githubusercontent.com/pi-hosted/pi-hosted/master/images/nginx-icon.png" width="30" /> | [NGINX Proxy Manager](https://github.com/NginxProxyManager/nginx-proxy-manager) | Nginx is a web server with a strong focus on high concurrency, performance and low memory usage. It can also act as a reverse proxy server for HTTP, HTTPS, SMTP, POP3, and IMAP protocols, as well as a load balancer and an HTTP cache. |
| <img src="https://res.cloudinary.com/canonical/image/fetch/f_auto,q_auto,fl_sanitize,c_fill,w_200,h_200/https://api.charmhub.io/api/v1/media/download/charm_Owpj9CsDEMZwVtup3ZTxxs0FtyvDqb2o_icon_5cef79c2d18f67464f39c8f2cf2d7ebb815b0071f04d3ffbb94f49fddd3ab666.png" width="30" /> | [Protainer](https://www.portainer.io/) | Lightweight service delivery platform for containerized applications that can be used to manage Docker, Swarm, Kubernetes and ACI environments. |
| <img src="https://raw.githubusercontent.com/pi-hosted/pi-hosted/master/images/bitwarden.png" width="30" /> | [Vaultwarden](https://github.com/dani-garcia/vaultwarden) | This is a Bitwarden server API implementation written in Rust compatible with upstream Bitwarden clients*, perfect for self-hosted deployment where running the official resource-heavy service might not be ideal. |
