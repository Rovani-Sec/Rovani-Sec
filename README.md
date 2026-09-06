# 🛡️ João Rovani

### Cybersecurity | Blue Team | SOC | Detection Engineering

Estudante de Segurança da Informação com foco em **Security Operations, Detection Engineering, análise de logs e investigação de incidentes**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-João%20Rovani-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joaorovani-sec)
[![GitHub](https://img.shields.io/badge/GitHub-Rovani--Sec-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rovani-Sec)
![SOC N1](https://img.shields.io/badge/Target-SOC%20N1-0B3D91?style=for-the-badge)

---

## 👨‍💻 Sobre mim

Sou estudante de **Segurança da Informação**, desenvolvendo experiência prática em **Blue Team e operações de SOC** por meio de laboratórios documentados.

Meu foco está em transformar telemetria e eventos de segurança em informações úteis para investigação, passando por etapas como:

- monitoramento e triagem de alertas;
- análise de Windows Event Logs e Sysmon;
- criação e validação de regras de detecção;
- correlação de eventos em SIEM;
- análise de processos e Command Line;
- investigação com Microsoft Defender XDR e KQL;
- mapeamento de comportamentos ao MITRE ATT&CK;
- documentação e resposta a incidentes.

**Fluxo praticado:**  
`Detection → Alert → Triage → Investigation → Classification → Response`

🎯 **Objetivo profissional:** primeira oportunidade como **SOC Analyst N1, Analista de Segurança Júnior ou Blue Team Júnior**.

---

## 🛠️ Stack principal

### 🔵 Security Operations

![Wazuh](https://img.shields.io/badge/Wazuh-SIEM-5A67D8?style=flat-square)
![Sysmon](https://img.shields.io/badge/Sysmon-Endpoint%20Telemetry-0078D4?style=flat-square)
![Defender XDR](https://img.shields.io/badge/Microsoft%20Defender-XDR-0078D4?style=flat-square)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE-ATT%26CK-EF3B2D?style=flat-square)
![SIEM](https://img.shields.io/badge/SIEM-Security%20Monitoring-4B5563?style=flat-square)

### 🖥️ Endpoint & Investigation

![Windows](https://img.shields.io/badge/Windows-Event%20Logs-0078D4?style=flat-square&logo=windows&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![KQL](https://img.shields.io/badge/KQL-Advanced%20Hunting-0078D4?style=flat-square)
![Log Analysis](https://img.shields.io/badge/Log-Analysis-374151?style=flat-square)
![Process Analysis](https://img.shields.io/badge/Process-Analysis-374151?style=flat-square)

### 🌐 Network & Lab

![pfSense](https://img.shields.io/badge/pfSense-Firewall-212121?style=flat-square)
![Suricata](https://img.shields.io/badge/Suricata-IDS%2FIPS-EF6C00?style=flat-square)
![Kali Linux](https://img.shields.io/badge/Kali-Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![TCP/IP](https://img.shields.io/badge/TCP%2FIP-Networking-2563EB?style=flat-square)

### 💻 Scripting & Versionamento

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

## 🚀 Projetos em Destaque

### 🛡️ PowerShell EncodedCommand — Detection & Investigation

Detecção e investigação de execução de **PowerShell com comando codificado em Base64**, utilizando Sysmon e regra customizada no Wazuh.

**Detecção:** `Sysmon Event ID 1` + `-EncodedCommand`  
**Regra:** `100106`  
**Análise:** processo pai/filho, `ParentCommandLine`, Base64 e PCRE2  
**MITRE ATT&CK:** `T1059.001` • `T1027`  
**Stack:** `Wazuh` `Sysmon` `Windows 10` `PowerShell` `CyberChef`

➡️ [Ver projeto completo](https://github.com/Rovani-Sec/soc-lab-comando-suspeito)

---

### ☁️ Windows Brute Force — Microsoft Defender XDR

Investigação de múltiplas falhas de autenticação utilizando **Microsoft Defender XDR, Advanced Hunting e KQL**.

**Telemetria:** `DeviceLogonEvents`  
**Detecção:** múltiplas falhas de autenticação por endpoint, conta e IP  
**Análise:** Advanced Hunting, Custom Detection e investigação de incidente  
**MITRE ATT&CK:** `T1110 — Brute Force`  
**Stack:** `Microsoft Defender XDR` `Defender for Endpoint` `KQL` `Windows 10` `Kali Linux` `SMB`

➡️ [Ver projeto completo](https://github.com/Rovani-Sec/soc-lab-bruteforce-detection-DefenderXDR)

---

### 🔐 Windows Authentication Brute Force — Wazuh

Detecção e investigação de tentativas de autenticação contra endpoint Windows utilizando **Wazuh SIEM** e correlação de eventos.

**Evento:** `Windows Event ID 4625`  
**Contexto:** `Logon Type 3` + IP de origem + usuário alvo  
**Regra:** `100100`  
**Resposta:** Active Response com bloqueio temporário do IP no Windows Firewall  
**MITRE ATT&CK:** `T1110` • `T1110.001`  
**Stack:** `Wazuh` `Windows Event Logs` `Sysmon` `Kali Linux` `Nmap` `NetExec`

➡️ [Ver projeto completo](https://github.com/Rovani-Sec/soc-lab-bruteforce-detection)

---

## 🧠 Competências Técnicas Demonstradas

| Competência | Evidência prática |
|---|---|
| **SIEM & Security Monitoring** | Monitoramento, correlação e investigação de eventos no Wazuh |
| **Detection Engineering** | Desenvolvimento e validação das Rules `100100` e `100106` |
| **Windows Event Analysis** | Investigação do Event ID `4625` |
| **Sysmon Analysis** | Análise do Event ID `1 — Process Creation` |
| **Process Investigation** | Processo pai/filho e `ParentCommandLine` |
| **Microsoft Defender XDR** | Advanced Hunting, Custom Detection e investigação |
| **KQL** | Consultas e correlação em `DeviceLogonEvents` |
| **Alert Triage** | Validação, contextualização e classificação de alertas |
| **Active Response** | Bloqueio temporário de IP com Wazuh |
| **PowerShell Analysis** | Investigação de `EncodedCommand` e Base64 |
| **MITRE ATT&CK** | Mapeamento das técnicas observadas |
| **Security Documentation** | Evidências e documentação técnica das investigações |

### 🧭 MITRE ATT&CK trabalhado nos laboratórios

![T1110](https://img.shields.io/badge/T1110-Brute%20Force-EF3B2D?style=flat-square)
![T1110.001](https://img.shields.io/badge/T1110.001-Password%20Guessing-EF3B2D?style=flat-square)
![T1059.001](https://img.shields.io/badge/T1059.001-PowerShell-EF3B2D?style=flat-square)
![T1027](https://img.shields.io/badge/T1027-Obfuscated%20Files%20or%20Information-EF3B2D?style=flat-square)

---

## 🎓 Formação & Certificações

### 🏫 Formação Acadêmica

**Tecnólogo em Segurança da Informação**  
Graduação em andamento.

**Previsão de conclusão:** 10/2027

### 🏅 Cisco Networking Academy

[![Endpoint Security](https://img.shields.io/badge/Cisco-Endpoint%20Security-1BA0D7?style=flat-square&logo=cisco&logoColor=white)](https://www.credly.com/badges/cf6b04e0-84f8-413d-ba65-9446bf10a5d8)

[![Introduction to Cybersecurity](https://img.shields.io/badge/Cisco-Introduction%20to%20Cybersecurity-1BA0D7?style=flat-square&logo=cisco&logoColor=white)](https://www.credly.com/badges/1768ae39-8b7b-4b9d-88b0-05f96b7e6469)

[![Networking Devices](https://img.shields.io/badge/Cisco-Networking%20Devices%20%26%20Initial%20Configuration-1BA0D7?style=flat-square&logo=cisco&logoColor=white)](https://www.credly.com/badges/e627a445-13eb-4360-91b1-d30adbcc615f)

[![Networking Basics](https://img.shields.io/badge/Cisco-Networking%20Basics-1BA0D7?style=flat-square&logo=cisco&logoColor=white)](https://www.credly.com/badges/60e5ed60-745b-47cd-b262-6421ccdb0b74)

---

## 📚 Desenvolvimento Contínuo

`LetsDefend` • `Hack The Box` • `Microsoft Learn` • `Cisco Networking Academy`

Áreas de aprofundamento:

- SOC Operations
- Incident Investigation
- Detection Engineering
- Threat Hunting
- Microsoft Security
- KQL
- Incident Response

---

## 📫 Contato

Tenho interesse em oportunidades de entrada em **SOC, Blue Team, Security Monitoring e Cybersecurity**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-João%20Rovani-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joaorovani-sec)
[![GitHub](https://img.shields.io/badge/GitHub-Rovani--Sec-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rovani-Sec)

---

**Blue Team • SOC • Detection Engineering • Incident Investigation**
