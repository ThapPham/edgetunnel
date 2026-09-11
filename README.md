# 🚀 edgetunnel 2.1
![Admin Page](./img.png)

[![Stars](https://img.shields.io/github/stars/cmliu/edgetunnel?style=flat-square&logo=github)](https://github.com/cmliu/edgetunnel/stargazers)
[![Forks](https://img.shields.io/github/forks/cmliu/edgetunnel?style=flat-square&logo=github)](https://github.com/cmliu/edgetunnel/network/members)
[![License](https://img.shields.io/github/license/cmliu/edgetunnel?style=flat-square)](https://github.com/cmliu/edgetunnel/blob/main/LICENSE)
[![Telegram](https://img.shields.io/badge/Telegram-Group-blue?style=flat-square&logo=telegram)](https://t.me/CMLiussss)
[![YouTube](https://img.shields.io/badge/YouTube-Channel-red?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=LeT4jQUh8ok)
[![zread](https://img.shields.io/badge/Ask_Zread-_.svg?style=flat-square&color=00b0aa&labelColor=000000&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTQuOTYxNTYgMS42MDAxSDIuMjQxNTZDMS44ODgxIDEuNjAwMSAxLjYwMTU2IDEuODg2NjQgMS42MDE1NiAyLjI0MDFWNC45NjAxQzEuNjAxNTYgNS4zMTM1NiAxLjg4ODEgNS42MDAxIDIuMjQxNTYgNS42MDAxSDQuOTYxNTZDNS4zMTUwMiA1LjYwMDEgNS42MDE1NiA1LjMxMzU2IDUuNjAxNTYgNC45NjAxVjIuMjQwMUM1LjYwMTU2IDEuODg2NjQgNS4zMTUwMiAxLjYwMDEgNC45NjE1NiAxLjYwMDFaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik00Ljk2MTU2IDEwLjM5OTlIMi4yNDE1NkMxLjg4ODEgMTAuMzk5OSAxLjYwMTU2IDEwLjY4NjQgMS42MDE1NiAxMS4wMzk5VjEzLjc1OTlDMS42MDE1NiAxNC4xMTM0IDEuODg4MSAxNC4zOTk5IDIuMjQxNTYgMTQuMzk5OUg0Ljk2MTU2QzUuMzE1MDIgMTQuMzk5OSA1LjYwMTU2IDE0LjExMzQgNS42MDE1NiAxMy43NTk5VjExLjAzOTlDNS42MDE1NiAxMC42ODY0IDUuMzE1MDIgMTAuMzk5OSA0Ljk2MTU2IDEwLjM5OTlaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik0xMy43NTg0IDEuNjAwMUgxMS4wMzg0QzEwLjY4NSAxLjYwMDEgMTAuMzk4NCAxLjg4NjY0IDEwLjM5ODQgMi4yNDAxVjQuOTYwMUMxMC4zOTg0IDUuMzEzNTYgMTAuNjg1IDUuNjAwMSAxMS4wMzg0IDUuNjAwMUgxMy43NTg0QzE0LjExMTkgNS42MDAxIDE0LjM5ODQgNS4zMTM1NiAxNC4zOTg0IDQuOTYwMVYyLjI0MDFDMTQuMzk4NCAxLjg4NjY0IDE0LjExMTkgMS42MDAxIDEzLjc1ODQgMS42MDAxWiIgZmlsbD0iI2ZmZiIvPgo8cGF0aCBkPSJNNCAxMkwxMiA0TDQgMTJaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik00IDEyTDEyIDQiIHN0cm9rZT0iI2ZmZiIgc3Ryb2tlLXdpZHRoPSIxLjUiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIvPgo8L3N2Zz4K&logoColor=ffffff)](https://zread.)(ai/cmliu/edgetunnel)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/cmliu/edgetunnel)

---

## 📖 Project Overview

**edgetunnel** is an edge computing decryption solution based on the CF Workers/Pages platform. It can efficiently process network traffic and provides a powerful management panel and flexible node configuration capabilities.

- 🖥️ **Demo Demo Site**: [https://EDT-Pages.github.io/admin](https://EDT-Pages.github.io/admin)

### ✨ Core Features

- 🛡️ **Protocol Support**: Supports mainstream protocols such as VLESS, Trojan, Shadowsocks, and deeply integrates encrypted transmission.
- 📊 **Admin Panel**: Built-in visual backend, supporting real-time configuration modifications, log viewing, and traffic statistics.
- 🛠️ **Flexible Deployment**: Fully compatible with CF Workers and CF Pages (GitHub / Upload).
- 🔄 **Subscription System**: Built-in automatic subscription generation and obfuscation conversion, compatible with mainstream clients (Clash, Sing-box, Surge, etc.).
- ⚡ **Performance Acceleration**: Supports custom ProxyIP, chain proxies for SOCKS5/HTTP, and optimized API selection to reduce network latency.
- 🌐 **Multi-device Compatibility**: Perfectly compatible with Windows, Android, iOS, MacOS, and various soft router firmware.

---

## 💡 Quick Deployment
>[!TIP]
> 📖 **Detailed Step-by-Step Guide**: [edgetunnel Deployment Guide](https://cmliussss.com/p/edt2/)

>[!WARNING]
> ⚠️ **Error 1101 Issue**: [Video Explanation](https://www.youtube.com/watch?v=r4uVTEJptdE)

### ⚙️ Workers Deployment

<details>
<summary><code><strong>"Workers Deployment Tutorial"</strong></code></summary>

1. Deploy CF Worker:
- Create a new Worker in the CF Worker console.
- Paste the contents of [worker.js](https://github.com/cmliu/edgetunnel/blob/main/_worker.js) into the Worker editor.
- In the left `Settings` tab, select `Variables` > `Add Variable`.
Fill in the variable name with **ADMIN**, and set the value as your admin password, then click `Save`.

2. Bind KV Namespace:
- In the `Binding` tab, select `Add Binding +` > `KV Namespace` > `Add Binding`, then choose an existing namespace or create a new namespace to bind.
- Fill in the `Variable Name` with **KV**, then click `Add Binding`.

3. Bind custom domains to Workers: 
- In the workers console, under the `Triggers` tab, click `Add Custom Domain`.
- Enter the subdomain you have transferred to the CF domain name resolution service, such as: `vless.google.com`, then click `Add Custom Domain`, and wait for the certificate to take effect.

4. Access the backend:
- Access `https://vless.google.com/admin` and enter the administrator password to log in to the backend.

</details>

### 🛠 Pages Upload Deployment Method **Highly Recommended!!!** [Illustrated Tutorial](https://cmliussss.com/p/edt2/)

<details>
<summary><code><strong>'Pages Upload File Deployment Text Tutorial'</strong></code></summary>

1. Deploy CF Pages:
- Download the [main.zip](https://github.com/cmliu/edgetunnel/archive/refs/heads/main.zip) file and give it a Star !!!
- In the CF Pages console, select `Upload Assets`, name your project, then click `Create Project`, upload the [main.zip](https://github.com/cmliu/edgetunnel/archive/refs/heads/main.zip) file you downloaded, and click `Deploy Site`.
- After deployment is complete, click `Continue Processing Site`, then select `Settings` > `Environment Variables` > **Make** to define variables for the production environment > `Add Variable`.
Enter **ADMIN** as the variable name, and the value as your admin password, then click `Save`.
- Return to the `Deployment` tab, click `Create New Deployment` in the lower right corner, re-upload the [main.zip](https://github.com/cmliu/edgetunnel/archive/refs/heads/main.zip) file, and then click `Save and Deploy`.

2. Bind KV Namespace:
- In the `Settings` tab, select `Bind` > `+ Add` > `KV Namespace`, then choose an existing namespace or create a new one to bind.
- Fill in `Variable Name` with **KV**, then click `Save` and retry deployment.

3. Bind a CNAME Custom Domain to Pages: [Video Tutorial](https://www.youtube.com/watch?v=LeT4jQUh8ok&t=851s)
- In the `Custom Domain` tab of the Pages console, click `Set Custom Domain` below.
- Enter your custom subdomain, noting not to use your root domain, for example:
If the domain assigned to you is `fuck.cloudns.biz`, then for the custom domain, enter `lizi.fuck.cloudns.biz`.
- According to CF's requirements, return your domain's DNS provider. After adding the CNAME record `edgetunnel.pages.dev` for the custom domain `lizi`, click `Activate Domain`.
   
4. Access the backend:
- Access `https://lizi.fuck.cloudns.biz/admin` and enter the administrator password to log in to the backend.

</details>

### 🛠 Pages + GitHub Deployment Method

<details>
<summary><code><strong>'Pages + GitHub Deployment Tutorial'</strong></code></summary>

1. Deploy to CF Pages:
- First Fork this project on Github, and give it a Star !!!
- In the CF Pages console, select `Connect to Git` then, select the `edgetunnel` project and click `Start Setup`.
- On the `Configure Build and Deployment` page at the bottom, select `Environment Variables (Advanced)` and then `Add Variable`.
Fill in the variable name with **ADMIN**, and the value as your admin password, then click `Save and Deploy` to complete.

2. Bind KV Namespace:
- Select `Bind` > `+ Add` > `KV Namespace` in the `Settings` tab, then choose an existing namespace or create a new one to bind.
- Fill in **KV** for `Variable Name`, click `Save`, and then retry deploying.

3. Bind a CNAME Custom Domain to Pages: [Video Tutorial](https://www.youtube.com/watch?v=LeT4jQUh8ok&t=851s)
- In the `Custom Domains` tab in the Pages console, click `Set Custom Domain` below.
- Enter your custom subdomain, note not to use your root domain, for example:
If the domain assigned to you is `fuck.cloudns.biz`, then for the custom domain, enter `lizi.fuck.cloudns.biz`;
- According to CF’s requirements, it will return your domain’s DNS provider. After adding the CNAME record for this custom domain `lizi` as `edgetunnel.pages.dev`, click `Activate Domain`.

4. Access the backend:
- Access `https://lizi.fuck.cloudns.biz/admin` and enter the administrator password to log in to the backend.

</details>

---

## 🗝️ Environment Variable Description

| Variable Name | Required | Example | Detailed Remarks |
| :--- | :---: | :--- | :--- |
| **ADMIN** | ✅ | `123456` | Password for logging into the backend admin panel |
| **KEY** | ❌ | `CMLiussss` | Quick subscription path key, access `/CMLiussss` to quickly get a node |
| **UUID** | ❌ | `90cd4a77-141a-43c9-991b-08263cfe9c10` | Forcibly fixed UUID, only supports the **UUIDv4** standard format |
| **PROXYIP** | ❌ | `proxyip.cmliussss.net:443` | Global custom reverse proxy IP |
| **URL** | ❌ | `https://cloudflare-error-page-3th.pages.dev` | Default home page disguise address (can be filled with a web page URL or `1101`) |
| **GO2SOCKS5** | ❌ | `blog.cmliussss.com`,`*.ip111.cn`,`*google.com` | List of domains forced to use SOCKS5 (`*` is global, domains separated by commas) |
| **DEBUG** | ❌ | `1` or `true` | **Developer mode**, debug log functionality (**console.log**) is **disabled** by default; set to `1` or `true` to **enable** debug logs |
| **OFF_LOG** | ❌ | `1` or `true` | KV log recording functionality is **enabled** by default; set to `1` or `true` to **disable** log recording |
| **BEST_SUB** | ❌ | `1` or `true` | The functionality as a **preferred subscription generator** is **disabled** by default; set to `1` or `true` to **enable** this functionality |
| **PRELOAD_RACE_DIAL** | ❌ | `1` or `true` | By default, the **preload race dialing** feature is **disabled**, set to `1` or `true` to **enable** the feature |
| **TCP_CONCURRENT_DIAL**   | ❌ | `2` | **TCP concurrent dialing number**, default value is `2`; after setting, it will no longer automatically reduce to single-channel based on China Mobile network |
| **PROXY_CONCURRENT_DIAL** | ❌ | `1` | **Proxy concurrent dialing number**, default value is `1`; the higher the value, the faster the connection speed, but the more frequent the IP switching |

---

## 🔧 Advanced Practical Tips
To modify the TOKEN in the **subscription address** and the UUID used for node verification, you can change the variables
1. Modify the value of the `ADMIN` or `KEY` variable to randomly change the TOKEN in the **subscription address** and the UUID used for node verification
2. Setting the `UUID` variable can force the TOKEN in the **subscription address** and the UUID used for node verification to be fixed. Note that it must be in the **UUIDv4** standard format, otherwise it will cause the node to be unusable.

This tool supports dynamically switching underlying proxy schemes through the **PATH path**:

- Specifying the `PROXYIP` case
```url
/proxyip=proxyip.cmliussss.net
/?proxyip=proxyip.cmliussss.net
```

- Designate SOCKS5 mode
```url
/socks5=user:password@127.0.0.1:1080
/?socks5=user:password@127.0.0.1:1080
/socks://dXNlcjpwYXNzd29yZA==@127.0.0.1:1080 (activates global SOCKS5 by default)
/socks5://user:password@127.0.0.1:1080 (activates global SOCKS5 by default)
```

- Specify `HTTP Proxy` example
```url
/http=user:password@127.0.0.1:1080
/http://user:password@127.0.0.1:8080 (default active global SOCKS5)
```

- Specify `Trojan fallback` examples (as the use case is for self-built integration, only Trojan inbound is used, and the fallback service must be the same password, non-WebSocket, non-TLS. At this time, UDP is tunneled to the fallback, excellent performance, and full functionality)
```url
/trojan=1.1.1.1:1234
```

---

## 💻 Client Compatibility

| Platform | Recommended Clients |
| :--- | :--- |
| **Windows** | [v2rayN](https://github.com/2dust/v2rayN/releases), [Hiddify](https://github.com/hiddify/hiddify-app/releases), [FlClash](https://github.com/chen08209/FlClash/releases), [mihomo-party](https://github.com/mihomo-party-org/clash-party/releases), [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev/releases), [Clashmi](https://github.com/KaringX/clashmi/releases), [FlyClash](https://github.com/GtxFury/FlyClash/releases), [Karing](https://github.com/KaringX/karing/releases), [Bettbox](https://github.com/appshubcc/Bettbox/releases) |
| **Android** | [v2rayNG](https://github.com/2dust/v2rayNG/releases), [ClashMetaForAndroid](https://github.com/MetaCubeX/ClashMetaForAndroid/releases/), [FlClash](https://github.com/chen08209/FlClash/releases), [Clashmi](https://github.com/KaringX/clashmi/releases), [Hiddify](https://github.com/hiddify/hiddify-app/releases), [NekoBox](https://github.com/MatsuriDayo/NekoBoxForAndroid/releases), [FlyClash](https://github.com/GtxFury/FlyClash/releases), [Karing](https://github.com/KaringX/karing/releases), [Bettbox](https://github.com/appshubcc/Bettbox/releases) |
| **iOS** | Surge, Shadowrocket, Stash, [Hiddify](https://github.com/hiddify/hiddify-app/releases), Loon, Egern, [Clashmi](https://clashmi.app/download), [Karing](https://karing.app/), Quantumult X |
| **macOS** | [FlClash](https://github.com/chen08209/FlClash/releases), [mihomo-party](https://github.com/mihomo-party-org/clash-party/releases), [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev/releases), Surge, [Clashmi](https://clashmi.app/download), [Karing](https://karing.app/), [FlyClash](https://github.com/GtxFury/FlyClash/releases) |
| **HarmonyOS** | [ClashBox](https://github.com/xiaobaigroup/ClashBox/releases) |
---

## ⭐ Project Popularity

![Stargazers over time](https://github.com/cmliu/cmliu/blob/main/star/edgetunnel.svg)

---

## 🙏 Special Thanks
### 💖 Sponsorship & Support - Provide cloud server to maintain [Subscription Conversion Service](https://sub.cmliussss.net/)
- [Yuusei Network](https://yuusei.io/)
- [VMRack](https://www.vmrack.net?ref_code=5Zk7eNhbgL7)

### 🛠 Open Source Code Reference
- [zizifn/edgetunnel](https://github.com/zizifn/edgetunnel)
- [3Kmfi6HP/EDtunnel](https://github.com/6Kmfi6HP/EDtunnel)
- [SHIJS1999/cloudflare-worker-vless-ip](https://github.com/SHIJS1999/cloudflare-worker-vless-ip)
- [Stanley-baby](https://github.com/Stanley-baby)
- [ACL4SSR](https://github.com/ACL4SSR/ACL4SSR/tree/master/Clash/config)
- [Stock God](https://t.me/CF_NAT/38889)
- [Workers/Pages Metrics](https://t.me/zhetengsha/3382)
- [Whiteforeground Brother](https://t.me/bestcfipas)
- [Mingyu](https://github.com/ymyuuu/workers-vless)
- [ToiCF/CF-Workers-HTTPS](https://github.com/ToiCF/CF-Workers-HTTPS)
- [ToiCF/CF-Workers-TURN](https://github.com/ToiCF/CF-Workers-TURN)
- [ToiCF/CF-Workers-SoftEther](https://github.com/ToiCF/CF-Workers-SoftEther)
- [eooce](https://github.com/eooce/Cloudflare-proxy)
- [Sukka](https://ip.skk.moe/)
- [zhangtaile](https://github.com/cmliu/edgetunnel/pull/999)
- [1345695](https://github.com/1345695/edcloudwasm)
- [ToiCF/GrainTCP](https://github.com/ToiCF/GrainTCP)
- [xream](https://github.com/cmliu/edgetunnel/pull/1359)

---

## ⚠️ Disclaimer

1. This project ("edgetunnel") is only for **educational, scientific research, and personal security testing** purposes.
2. Users must strictly comply with the laws and regulations of their respective regions when downloading or using the code of this project.
3. The author **cmliu** assumes no responsibility for any actions or consequences resulting from the abuse of this project's code.
4. This project is not liable for any direct or indirect damages caused by the use of the code.
5. It is recommended to delete the deployment related to this project within 24 hours after testing is completed.

---

**If you find the project helpful, please give a Star 🌟 - it's the greatest encouragement for me!**
