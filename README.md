<div align="center">

```
____________  ___   _   _______ _____ 
| ___ \ ___ \/ _ \ | \ | |  _  \  _  |
| |_/ / |_/ / /_\ \|  \| | | | | | | |
| ___ \    /|  _  || . ` | | | | | | |
| |_/ / |\ \| | | || |\  | |/ /\ \_/ /
\____/\_| \_\_| |_/\_| \_/___/  \___/ 
```

```
[ BRANDO ] — Offensive Security Specialist & Infrastructure Engineer
```

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=00FF41&center=true&vCenter=true&width=700&lines=Offensive+Security+%7C+Red+Team+%7C+Hardware+Hacking;Custom+Pentest+Tools+%7C+Raspberry+Pi+Pico+%7C+HID+Attack;OSINT+%7C+CVE+Research+%7C+Network+Exploitation;Infrastructure+as+Code+%7C+AWS+%7C+Cloud+Security)



</div>

---

## $ whoami

```bash
> alias: BRANDO
> role:  Offensive Security Specialist | Pentester | Infrastructure Engineer
> base:  São Paulo, BR — Capital
> focus: Red Team Operations | Custom Tool Development | Cloud Security
```

Profissional de segurança ofensiva com experiência prática em pentest, desenvolvimento de ferramentas próprias e infraestrutura em nuvem. Não executo apenas ferramentas prontas — **eu as construo**.

Minha abordagem combina mentalidade de adversário com capacidade de engenharia, o que me permite ir além do relatório padrão: entendo o sistema, exploro a fundo e proponho correções reais.

> *"Tools are just tools. The weapon is the mind behind them."*

---

## 🔴 Offensive Security

### Hardware Hacking & Custom Tool Development

```
┌─────────────────────────────────────────────────────────────────────┐
│  PROJETO: HID Attack Tool — Raspberry Pi Pico                       │
├─────────────────────────────────────────────────────────────────────┤
│  Hardware : Raspberry Pi Pico (emulação de teclado HID)             │
│  Payload  : WinPEAS — enumeração automatizada de sistemas Windows   │
│  Output   : resultado.txt + coleta via nmap integrado               │
│  Scripts  : code.py, run.bat, lib customizada                       │
│  Target   : privilege escalation enum em sistemas físicos           │
│                                                                     │
│  /hid-attack/                                                       │
│  ├── code.py        ← payload principal (CircuitPython)             │
│  ├── run.bat        ← execução Windows                              │
│  ├── lib/           ← bibliotecas customizadas                      │
│  ├── nmap           ← scanner integrado                             │
│  └── resultado.txt  ← output de enumeração                         │
└─────────────────────────────────────────────────────────────────────┘
```

---

### Wireless Exploitation

```python
capabilities = {
    "WPA2/WPA3": [
        "handshake capture",
        "PMKID attack",
        "network poisoning",
        "deauth flood"
    ],
    "Wi-Fi Spoofing": [
        "evil twin AP",
        "rogue access point",
        "captive portal injection"
    ],
    "Traffic Analysis": [
        "full packet capture",
        "MITM interception",
        "protocol dissection",
        "credential sniffing"
    ],
    "tools": [
        "Aircrack-ng", "Hcxdumptool", "Hcxtools",
        "Bettercap", "Wifite", "Wireshark", "tcpdump"
    ]
}
```

---

### Credential & Hash Operations

```
DUMP EXTRACTION ──► SAM dump / LSASS / /etc/shadow / memory forensics
HASH RECOGNITION ─► MD5 · SHA1 · SHA256 · NTLM · bcrypt · WPA PMKID
CRACKING ─────────► Hashcat (GPU rules) · John the Ripper · custom masks
BRUTEFORCE ───────► Hydra · Medusa · CrackMapExec · custom wordlists
```

---

### Network & System Exploitation

| Técnica | Ferramentas | Resultado |
|---|---|---|
| Reconhecimento ativo | Nmap, Masscan, Amass | Mapa completo da superfície de ataque |
| Exploração de CVEs | Metasploit, Nuclei, Exploit-DB | Acesso não autorizado controlado |
| Web Attacks | ZAP, Burp Suite, sqlmap, ffuf | XSS, SQLi, LFI, IDOR, RFI |
| Captura de tráfego | Wireshark, mitmproxy, Ettercap | Credenciais e sessões interceptadas |
| Engenharia Social | SET, phishing técnico | Vetor humano de comprometimento |
| Enumeração de sistemas | WinPEAS, LinPEAS, BloodHound | Privilege escalation paths |

---

## 🕵️ OSINT Operations

### WhatsApp Intelligence
Coleta automatizada de metadados públicos — dispositivos vinculados, configurações de privacidade, verificação de contas Business, análise de exposição via RapidAPI.

### Camera & CCTV Reconnaissance
Mapeamento de câmeras expostas publicamente, identificação de painéis sem autenticação, análise de sistemas CFTV corporativos.

### Web Recon & CVE Correlation
```bash
# Pipeline de reconhecimento — by BRANDO
amass enum -d target.com -o subdomains.txt
nmap -sV -sC --script vuln -iL subdomains.txt
nuclei -l subdomains.txt -severity critical,high,medium
# correlação automática com NIST NVD + MITRE CVE
```

---

## ☁️ Cloud & Infrastructure as Code

```yaml
author: BRANDO
cloud: AWS
services:
  compute: [EC2, Lambda, ECS]
  storage: [S3, DynamoDB]
  iot: [IoT Core, IoT Rules, Shadow State]
  messaging: [MQTT, SQS]
iac:
  - CloudFormation (YAML templates)
  - Docker / Docker Compose
  - Python automation & boto3
cloud_security_assessments:
  - IAM misconfiguration & privilege escalation
  - S3 bucket exposure & ACL analysis
  - Lambda function security review
  - CloudTrail log analysis
  - Security Group rule auditing
```

---

## 🛠️ Stack Técnico

**Linguagens**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![YAML](https://img.shields.io/badge/yaml-%23ffffff.svg?style=for-the-badge&logo=yaml&logoColor=151515)

**Infraestrutura**
![AWS](https://img.shields.io/badge/AWS-000.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-E34F26?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-35495E?style=for-the-badge&logo=ubuntu&logoColor=2CA5E0)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

**Offensive Security**
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)

---

## 🧰 Ferramentas Desenvolvidas por BRANDO

```
◆ HID Attack Tool      Raspberry Pi Pico + WinPEAS, emulação HID para
                       enumeração física de sistemas Windows

◆ WhatsApp OSINT       Extração automatizada de metadados e análise
                       de exposição pública via API

◆ Network Recon Suite  Scripts customizados de reconhecimento com
                       correlação automática de CVEs

◆ [em construção]      Novas ferramentas ofensivas — repositórios em breve
```

---

## ⚖️ Conduta

```
Engagements realizados com escopo definido e autorização explícita.
Conformidade: Lei 12.737/2012 · LGPD · Ética Profissional em Segurança.
```

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=brand4ilde&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=brand4ilde&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117)

---

```bash
$ whoami
BRANDO
$ echo "Offensive Security | Custom Tools | Red Team"
Offensive Security | Custom Tools | Red Team
```

![Visitors](https://komarev.com/ghpvc/?username=brand4ilde&color=00ff41&style=flat-square&label=PROFILE+VIEWS)

</div>
