<div align="center">

# 🛡️ João Rovani

### Cybersecurity | Blue Team | SOC Analyst

Estudante de Segurança da Informação com foco em **Security Operations,  
Detection Engineering, análise de logs e investigação de incidentes**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-João%20Rovani-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joaorovani-sec)
[![GitHub](https://img.shields.io/badge/GitHub-Rovani--Sec-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rovani-Sec)

</div>

---

## 👨‍💻 Sobre mim

Sou estudante de **Segurança da Informação**, atualmente desenvolvendo experiência prática em **Blue Team e operações de SOC**.

Meu foco está em transformar eventos e logs em informações úteis para investigação, trabalhando com cenários que envolvem:

- monitoramento e triagem de alertas;
- análise de Windows Event Logs e Sysmon;
- criação e validação de regras de detecção;
- correlação de eventos em SIEM;
- análise de processos e Command Line;
- mapeamento de comportamentos ao MITRE ATT&CK;
- investigação e documentação de incidentes;
- resposta automatizada em cenários controlados.

Meus laboratórios são construídos para reproduzir fluxos próximos aos encontrados em operações de segurança:

**Detection → Alert → Triage → Investigation → Classification → Response**

🎯 **Objetivo profissional:** primeira oportunidade como **SOC Analyst N1 / Analista de Segurança Júnior / Blue Team Júnior**.

---

## 🛠️ Stack principal

### Security Operations

`Wazuh` `Sysmon` `Microsoft Defender XDR` `Windows Event Logs` `MITRE ATT&CK`

### Endpoint & Investigation

`Windows 10` `PowerShell` `KQL` `Log Analysis` `Process Analysis`

### Network & Lab

`pfSense` `Suricata` `Kali Linux` `TCP/IP`

### Scripting & Versionamento

`Python` `PowerShell` `Git` `GitHub`

---

## 🚀 Projetos em Destaque

Projetos práticos desenvolvidos em laboratório para exercitar atividades próximas às realizadas em operações de **SOC e Blue Team**, incluindo geração de telemetria, criação de detecções, triagem, investigação e resposta.

### 🛡️ PowerShell EncodedCommand — Detection & Investigation

Laboratório focado na detecção e investigação de execução de **PowerShell com comandos codificados em Base64**, utilizando telemetria do Sysmon e uma regra customizada no Wazuh.

**Principais atividades:**

- Análise do **Sysmon Event ID 1 — Process Creation**
- Investigação de processo pai/filho
- Análise de `ParentCommandLine`
- Identificação de `-EncodedCommand`
- Decodificação de payload Base64
- Desenvolvimento da **Rule 100106**
- Uso de PCRE2 na lógica de detecção
- Mapeamento para **MITRE ATT&CK**
- Classificação do alerta após investigação

**Stack:**  
`Wazuh` `Sysmon` `Windows 10` `PowerShell` `CyberChef` `MITRE ATT&CK`

**MITRE ATT&CK:**  
`T1059.001 — PowerShell` • `T1027 — Obfuscated Files or Information`

➡️ [Ver projeto completo](https://github.com/Rovani-Sec/soc-lab-comando-suspeito)

---

### ☁️ Windows Brute Force — Microsoft Defender XDR

Laboratório de detecção e investigação de múltiplas falhas de autenticação Windows utilizando **Microsoft Defender XDR**, Advanced Hunting e KQL.

O projeto percorre o ciclo completo entre geração da atividade, hunting, desenvolvimento da lógica de detecção e investigação do incidente.

**Principais atividades:**

- Análise de `DeviceLogonEvents`
- Investigação com **Advanced Hunting**
- Desenvolvimento de consultas em **KQL**
- Correlação por endpoint, conta e IP de origem
- Threshold de múltiplas falhas de autenticação
- Criação de **Custom Detection**
- Geração e investigação de incidente
- Triagem e classificação da atividade
- Mapeamento para **MITRE ATT&CK**

**Stack:**  
`Microsoft Defender XDR` `Defender for Endpoint` `KQL` `Windows 10` `Kali Linux` `SMB`

**MITRE ATT&CK:**  
`T1110 — Brute Force`

➡️ [Ver projeto completo](https://github.com/Rovani-Sec/soc-lab-bruteforce-detection-DefenderXDR)

---

### 🔐 Windows Authentication Brute Force — Wazuh

Laboratório de monitoramento e investigação de múltiplas tentativas de autenticação contra um endpoint Windows, utilizando **Wazuh SIEM**.

A detecção utiliza correlação de eventos de autenticação para transformar falhas individuais em um alerta contextualizado de possível Brute Force.

**Principais atividades:**

- Reconhecimento de serviço SMB
- Análise do **Windows Event ID 4625**
- Identificação de `Logon Type 3`
- Análise de IP de origem e usuário alvo
- Coleta de eventos pelo Wazuh Agent
- Correlação de múltiplas falhas de autenticação
- Desenvolvimento da **Rule 100100**
- Investigação e classificação do alerta
- Análise de estratégias de resposta e mitigação

**Stack:**  
`Wazuh` `Windows Event Logs` `Sysmon` `Windows 10` `Kali Linux` `Nmap` `NetExec`

**MITRE ATT&CK:**  
`T1110 — Brute Force` • `T1110.001 — Password Guessing`

➡️ [Ver projeto completo](https://github.com/Rovani-Sec/soc-lab-bruteforce-detection)

---

### 🔄 Fluxo praticado nos laboratórios

```text
Activity / Simulation
        ↓
     Telemetry
        ↓
     Detection
        ↓
       Alert
        ↓
      Triage
        ↓
   Investigation
        ↓
 Classification
        ↓
 Response / Escalation
        ↓
  Documentation
```
---

## 🎓 Formação & Certificações

### 🏫 Formação Acadêmica

**Tecnólogo em Segurança da Informação**  
Graduação em andamento, com foco em fundamentos de segurança, redes, sistemas operacionais, infraestrutura e proteção de ambientes computacionais.
```text
previsão de término em: 10/2027
```
---

### 🏅 Cisco Networking Academy

#### 🛡️ Endpoint Security

Formação voltada à segurança de endpoints, ameaças, vulnerabilidades e mecanismos de proteção.

[![Credly](https://img.shields.io/badge/Credly-Ver%20Badge-FF6B00?style=flat-square&logo=credly&logoColor=white)](https://www.credly.com/badges/cf6b04e0-84f8-413d-ba65-9446bf10a5d8)

---

#### 🔐 Introduction to Cybersecurity

Fundamentos de Cybersecurity, ameaças, vulnerabilidades, segurança digital e princípios de proteção.

[![Credly](https://img.shields.io/badge/Credly-Ver%20Badge-FF6B00?style=flat-square&logo=credly&logoColor=white)](https://www.credly.com/badges/1768ae39-8b7b-4b9d-88b0-05f96b7e6469)

---

#### 🌐 Networking Devices and Initial Configuration

Fundamentos de dispositivos de rede e configuração inicial de infraestrutura Cisco.

[![Credly](https://img.shields.io/badge/Credly-Ver%20Badge-FF6B00?style=flat-square&logo=credly&logoColor=white)](https://www.credly.com/badges/e627a445-13eb-4360-91b1-d30adbcc615f)

---

#### 🌍 Networking Basics

Fundamentos de redes, endereçamento e comunicação entre dispositivos.

[![Credly](https://img.shields.io/badge/Credly-Ver%20Badge-FF6B00?style=flat-square&logo=credly&logoColor=white)](https://www.credly.com/badges/60e5ed60-745b-47cd-b262-6421ccdb0b74)

---

### 📚 Desenvolvimento Contínuo

Estudos complementares direcionados a operações de segurança e defesa cibernética através de:

`LetsDefend` `Hack The Box` `Microsoft Learn` `Cisco Networking Academy`

Áreas de aprofundamento:

- SOC Operations
- Incident Investigation
- Detection Engineering
- Threat Hunting
- Microsoft Security
- KQL
- Incident Response
