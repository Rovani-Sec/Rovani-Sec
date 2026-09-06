🛡️ João Rovani

Cybersecurity | Blue Team | SOC | Detection Engineering

Estudante de Segurança da Informação com foco em Security Operations, Detection Engineering, análise de logs e investigação de incidentes.






👨‍💻 Sobre mim

Sou estudante de Segurança da Informação, desenvolvendo experiência prática em Blue Team e operações de SOC por meio de laboratórios documentados.

Meu foco está em transformar telemetria e eventos de segurança em informações úteis para investigação, passando por etapas como:

monitoramento e triagem de alertas;

análise de Windows Event Logs e Sysmon;

criação e validação de regras de detecção;

correlação de eventos em SIEM;

análise de processos e Command Line;

investigação com Microsoft Defender XDR e KQL;

mapeamento de comportamentos ao MITRE ATT&CK;

documentação e resposta a incidentes.

Fluxo praticado:
Detection → Alert → Triage → Investigation → Classification → Response

🎯 Objetivo profissional: primeira oportunidade como SOC Analyst N1, Analista de Segurança Júnior ou Blue Team Júnior.

🛠️ Stack principal

🔵 Security Operations







🖥️ Endpoint & Investigation







🌐 Network & Lab






💻 Scripting & Versionamento





🚀 Projetos em Destaque

🛡️ PowerShell EncodedCommand — Detection & Investigation

Detecção e investigação de execução de PowerShell com comando codificado em Base64, utilizando Sysmon e regra customizada no Wazuh.

Detecção: Sysmon Event ID 1 + -EncodedCommand
Regra: 100106
Análise: processo pai/filho, ParentCommandLine, Base64 e PCRE2
MITRE ATT&CK: T1059.001 • T1027
Stack: Wazuh Sysmon Windows 10 PowerShell CyberChef

➡️ Ver projeto completo

☁️ Windows Brute Force — Microsoft Defender XDR

Investigação de múltiplas falhas de autenticação utilizando Microsoft Defender XDR, Advanced Hunting e KQL.

Telemetria: DeviceLogonEvents
Detecção: múltiplas falhas de autenticação por endpoint, conta e IP
Análise: Advanced Hunting, Custom Detection e investigação de incidente
MITRE ATT&CK: T1110 — Brute Force
Stack: Microsoft Defender XDR Defender for Endpoint KQL Windows 10 Kali Linux SMB

➡️ Ver projeto completo

🔐 Windows Authentication Brute Force — Wazuh

Detecção e investigação de tentativas de autenticação contra endpoint Windows utilizando Wazuh SIEM e correlação de eventos.

Evento: Windows Event ID 4625
Contexto: Logon Type 3 + IP de origem + usuário alvo
Regra: 100100
Resposta: Active Response com bloqueio temporário do IP no Windows Firewall
MITRE ATT&CK: T1110 • T1110.001
Stack: Wazuh Windows Event Logs Sysmon Kali Linux Nmap NetExec

➡️ Ver projeto completo

🧠 Competências Técnicas Demonstradas

Competência

Evidência prática

SIEM & Security Monitoring

Monitoramento, correlação e investigação de eventos no Wazuh

Detection Engineering

Desenvolvimento e validação das Rules 100100 e 100106

Windows Event Analysis

Investigação do Event ID 4625

Sysmon Analysis

Análise do Event ID 1 — Process Creation

Process Investigation

Processo pai/filho e ParentCommandLine

Microsoft Defender XDR

Advanced Hunting, Custom Detection e investigação

KQL

Consultas e correlação em DeviceLogonEvents

Alert Triage

Validação, contextualização e classificação de alertas

Active Response

Bloqueio temporário de IP com Wazuh

PowerShell Analysis

Investigação de EncodedCommand e Base64

MITRE ATT&CK

Mapeamento das técnicas observadas

Security Documentation

Evidências e documentação técnica das investigações

🧭 MITRE ATT&CK trabalhado nos laboratórios






🎓 Formação & Certificações

🏫 Formação Acadêmica

Tecnólogo em Segurança da Informação
Graduação em andamento.

Previsão de conclusão: 10/2027

🏅 Cisco Networking Academy









📚 Desenvolvimento Contínuo

LetsDefend • Hack The Box • Microsoft Learn • Cisco Networking Academy

Áreas de aprofundamento:

SOC Operations

Incident Investigation

Detection Engineering

Threat Hunting

Microsoft Security

KQL

Incident Response

📫 Contato

Tenho interesse em oportunidades de entrada em SOC, Blue Team, Security Monitoring e Cybersecurity.




Blue Team • SOC • Detection Engineering • Incident Investigation
