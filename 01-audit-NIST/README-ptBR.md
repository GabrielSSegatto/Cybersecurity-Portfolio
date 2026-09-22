*Leia em outros idiomas: [English](README.md), [Português](README-ptBR.md).*

# Auditoria Interna de Segurança e Conformidade

## Visão Geral do Projeto
Este projeto simula uma auditoria interna de segurança para uma empresa fictícia (Botium Toys). O objetivo foi avaliar a postura atual de segurança, identificar vulnerabilidades no gerenciamento de ativos e garantir a conformidade com regulamentações e frameworks internacionais.

## Objetivos
* Realizar uma avaliação de riscos baseada no **Framework de Cibersegurança do NIST (CSF)**.
* Avaliar a implementação de controles administrativos, técnicos e físicos.
* Verificar a adequação e conformidade para **PCI-DSS**, **GDPR** e **SOC (Tipos 1 e 2)**.

## Ferramentas e Frameworks Utilizados
* **NIST CSF** (Identificar, Proteger, Detectar, Responder, Recuperar)
* **Padrões de Conformidade:** GDPR, PCI-DSS, SOC
* Avaliação de Riscos & Análise de Lacunas (*Gap Analysis*)

## Principais Descobertas e Recomendações
Durante a auditoria, várias lacunas críticas foram identificadas, como a ausência de um Sistema de Detecção de Intrusões (IDS), gerenciamento inadequado de senhas e não conformidade com o Princípio do Privilégio Mínimo. 

Para mitigar esses riscos, um plano de ação de 5 etapas foi recomendado às partes interessadas (*stakeholders*):
1. Implantar Criptografia de Dados (em repouso e em trânsito).
2. Implementar o Gerenciamento de Identidade e Acesso (IAM) aplicando o Privilégio Mínimo.
3. Adotar um Sistema Centralizado de Gerenciamento de Senhas com MFA.
4. Estabelecer uma rotina de Backups e um Plano de Recuperação de Desastres (DRP).
5. Instalar um Sistema de Detecção de Intrusões (IDS).

## Documentação
* [Visualizar o Contexto do Cenário (Avaliação de Risco da Botium Toys)](./Context_Botium_Toys.pdf)
* [Visualizar o Relatório Completo de Auditoria e Conformidade (Minha Solução)](./Audit_Report_Botium_Toys.pdf)