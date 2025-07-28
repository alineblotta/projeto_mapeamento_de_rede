
## Projeto Técnico: Mapeamento de Rede Corporativa - Lab Docker

Este projeto é parte da Trilha de Formação em Cybersecurity – Módulo 1.
O objetivo é simular uma rede corporativa segmentada com estações de trabalho, servidores e dispositivos pessoais para que você possa treinar suas habilidades de reconhecimento e análise de exposição.

## Escopo do Projeto

Este projeto envolveu:

- A criação de um ambiente Docker com múltiplos containers representando diferentes segmentos de rede (Corp, Infra, Guest).
- Aplicação de técnicas de reconhecimento passivo e ativo utilizando ferramentas como `NETDISCOVER`, `PING`, `NMAP` e `RUSTSCAN`.
- Identificação de serviços inseguros e portas abertas, seguido de recomendações técnicas de mitigação.
- Registro de comandos executados, respostas dos hosts e evidências visuais por meio de screenshots incluídos nos anexos do relatório.

## Diagnóstico Realizado

A análise técnica revelou:

- Uso de serviços legados sem criptografia (ex: FTP, SMB, LDAP).
- Diversas portas abertas sem restrições adequadas.
- Ausência de autenticação forte em serviços críticos.
- Oportunidades para segmentação lógica via VLANs e reforço de regras de firewall.

## Recomendações

- Atualização de protocolos (ex: FTPS, LDAPS, HTTPS).
- Restrições de acesso por porta, IP e protocolo.
- Desativação de serviços desnecessários e implementação de firewalls internos.
- Treinamentos para colaboradores visando reforço da cultura de segurança.
