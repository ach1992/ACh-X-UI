# 3x-ui
![](https://img.shields.io/github/v/release/ach1992/ACh-X-UI.svg)
![](https://img.shields.io/github/actions/workflow/status/ach1992/ACh-X-UI/release.yml.svg)
[![GO Version](https://img.shields.io/github/go-mod/go-version/ach1992/ACh-X-UI.svg)](https://img.shields.io/github/go-mod/go-version/ach1992/ACh-X-UI)
[![Downloads](https://img.shields.io/github/downloads/ach1992/ACh-X-UI/total.svg)](https://img.shields.io/github/downloads/ach1992/ACh-X-UI/total)
[![License](https://img.shields.io/badge/license-GPL%20V3-blue.svg?longCache=true)](https://www.gnu.org/licenses/gpl-3.0.en.html)

> **Disclaimer: This project is only for personal learning and communication, please do not use it for illegal purposes, please do not use it in a production environment**

xray panel supporting multi-protocol, **Multi-lang (English,Farsi,Chinese)**

# Install & Upgrade

```
bash <(curl -Ls https://raw.githubusercontent.com/ach1992/ACh-X-UI/master/install.sh)
```

# SSL
```
apt-get install certbot -y
certbot certonly --standalone --agree-tos --register-unsafely-without-email -d yourdomain.com
certbot renew --dry-run
```

**If you think this project is helpful to you, you may wish to give a** :star2: 

# Default settings

- Port: 2053
- username and password will be generated randomly you can see them after you install it (x-ui "7")
- database path: /etc/x-ui/x-ui.db

before you set ssl on settings
- http:// ip or domain:2053/xui

After you set ssl on settings 
- https://yourdomain:2053/xui

**for enable traffic for users you should do :**

**xray Configuration :**
```json
  "policy": {
    "levels": {
      "0": {
        "statsUserUplink": true,
        "statsUserDownlink": true
      }
    },

    "system": {
      "statsInboundDownlink": true,
      "statsInboundUplink": true
    }
  },
  "routing": {
```

# suggestion system
- Ubuntu 20.04+
- Debian 10
- CentOS 8

# pic

![1](https://raw.githubusercontent.com/ach1992/ACh-X-UI/main/media/1.png)
![2](https://raw.githubusercontent.com/ach1992/ACh-X-UI/main/media/2.png)
![3](https://raw.githubusercontent.com/ach1992/ACh-X-UI/main/media/3.png)
![4](https://raw.githubusercontent.com/ach1992/ACh-X-UI/main/media/4.png)

# a special thanks to
- [vaxilu](https://github.com/vaxilu/)
- [HexaSoftwareTech](https://github.com/HexaSoftwareTech/)
- [diditra](https://github.com/diditra/)
- [FranzKafkaYu](https://github.com/FranzKafkaYu)
- [alireza0](https://github.com/alireza0/)


## Stargazers over time

[![Stargazers over time](https://starchart.cc/ach1992/ACh-X-UI.svg)](https://starchart.cc/ach1992/ACh-X-UI)
