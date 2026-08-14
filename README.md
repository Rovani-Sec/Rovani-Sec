# Olá, eu sou João Rovani

## 🛡️ Segurança da Informação | Blue Team | SOC Analyst N1

🎓 Tecnólogo em Segurança da Informação  
🔵 Blue Team • SOC • Security Monitoring  
🔎 SIEM • Log Analysis • Endpoint Security • Threat Detection

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joaorovani-sec)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rovani-Sec)

---

## 🚀 Sobre mim

Sou estudante de **Segurança da Informação**, construindo minha carreira em **Cybersecurity**, com foco em **Blue Team e Security Operations Center (SOC)**.

Busco minha primeira oportunidade profissional como **SOC Analyst N1**, com interesse em monitoramento de segurança, triagem de alertas, análise de logs, investigação inicial de incidentes e resposta.

Meu desenvolvimento combina **formação acadêmica, cursos especializados e laboratórios práticos**, buscando transformar conhecimento teórico em habilidades aplicáveis a cenários reais de segurança.

Tenho desenvolvido laboratórios utilizando **Wazuh, Sysmon, Windows, Kali Linux e Python**, simulando ataques, analisando eventos e documentando o processo de investigação.

---

## 🧠 Principais Habilidades

### 🔵 SOC & Blue Team

![SOC](https://img.shields.io/badge/SOC-Security%20Operations-0A66C2?style=flat-square)
![SIEM](https://img.shields.io/badge/SIEM-Security%20Monitoring-5E5E5E?style=flat-square)
![Incident Response](https://img.shields.io/badge/Incident%20Response-Detection%20%26%20Investigation-8B0000?style=flat-square)
![Threat Hunting](https://img.shields.io/badge/Threat%20Hunting-Blue%20Team-1E7A46?style=flat-square)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-Framework-EF3B2D?style=flat-square)

- Security Monitoring
- Alert Triage
- Log Analysis
- Incident Investigation
- Incident Response
- Threat Detection
- Threat Hunting
- IOC Analysis
- SIEM
- MITRE ATT&CK

### 🖥️ Windows & Endpoint Security

![Windows](https://img.shields.io/badge/Windows-Security-0078D6?style=flat-square&logo=windows&logoColor=white)
![Sysmon](https://img.shields.io/badge/Sysmon-Endpoint%20Monitoring-0078D4?style=flat-square)
![Windows Event Logs](https://img.shields.io/badge/Windows-Event%20Logs-0078D4?style=flat-square)

- Windows Event Logs
- Event ID 4624
- Event ID 4625
- Authentication Analysis
- Logon Types
- Sysmon
- Endpoint Monitoring
- Windows Security

### 🛡️ Security Tools

![Wazuh](https://img.shields.io/badge/Wazuh-SIEM-4E5A65?style=flat-square)
![Microsoft Defender](https://img.shields.io/badge/Microsoft-Defender-0078D4?style=flat-square)
![Microsoft Intune](https://img.shields.io/badge/Microsoft-Intune-0078D4?style=flat-square)
![Microsoft Entra](https://img.shields.io/badge/Microsoft-Entra%20ID-5E5E5E?style=flat-square)
![KQL](https://img.shields.io/badge/KQL-Query%20Language-0078D4?style=flat-square)

- Wazuh
- Microsoft Defender (em desenvolvimento)
- Microsoft Intune.  (em desenvolvimento)  
- Microsoft Entra ID.(em desenvolvimento)
- Sysmon
- KQL (em desenvolvimento)
- Kali Linux
- VirtualBox

### 💻 Scripting & Development

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

- Python
- PowerShell
- Git
- GitHub

### 🌐 Networking

![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![TCP/IP](https://img.shields.io/badge/TCP%2FIP-Networking-1BA0D7?style=flat-square)

- TCP/IP
- Network Fundamentals
- Network Security Fundamentals
- Cisco Networking
- Cisco Packet Tracer

---

## 🚨 Projeto em Destaque

### 🔥 SOC Lab — Windows Authentication Brute Force Detection

Laboratório prático desenvolvido para simular um cenário de **Brute Force contra autenticação Windows** e realizar sua detecção, análise e investigação através do **Wazuh**.

**Tecnologias:**

`Wazuh` `Sysmon` `Windows 10` `Kali Linux` `Python` `MITRE ATT&CK`

**Práticas realizadas:**

- Simulação de tentativas de autenticação
- Geração de eventos Windows
- Análise do **Event ID 4625**
- Coleta de logs através do Wazuh Agent
- Correlação de eventos
- Criação de lógica de detecção
- Investigação da origem dos eventos
- Identificação de comportamento de Brute Force
- Documentação do incidente
- Aplicação do MITRE ATT&CK
- Active Response para bloqueio temporário do IP atacante

### 🏗️ Arquitetura

```text
Kali Linux
   │
   │ Authentication Attempts
   ▼
Windows 10 + Sysmon
   │
   │ Security Events
   ▼
Wazuh Agent
   │
   ▼
Wazuh Manager / SIEM
   │
   ▼
Detection & Alert
   │
   ▼
Active Response
```