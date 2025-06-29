# 💻 Desafio Prático - Gerenciamento de Máquinas Virtuais no Azure (AZ-104)

Este repositório foi criado como parte do desafio prático proposto pela DIO em parceria com a Microsoft. Ele contém resumos, anotações e dicas sobre os principais tópicos abordados no curso de preparação para a certificação **Azure Administrator (AZ-104)**.

O objetivo é servir como material de apoio para revisões futuras e para auxiliar outros profissionais que estão se preparando para atuar com infraestrutura em nuvem usando o Microsoft Azure.

---

# 🧭 Sumário

- [1. Introdução](#1-introdução)
- [2. Gerenciamento de Identidade e Acesso](#2-gerenciamento-de-identidade-e-acesso)
- [3. Governança e Conformidade](#3-governança-e-conformidade)
- [4. Gerenciamento de Recursos no Azure](#4-gerenciamento-de-recursos-no-azure)
- [5. Redes Virtuais no Azure](#5-redes-virtuais-no-azure)
- [6. Armazenamento no Azure](#6-armazenamento-no-azure)
- [7. Máquinas Virtuais e Alta Disponibilidade](#7-máquinas-virtuais-e-alta-disponibilidade)
- [8. Conclusão e Dicas Finais](#8-conclusão-e-dicas-finais)
- [🔗 Recursos Complementares](#-recursos-complementares)


# 1. Introdução

Curso: **Introdução ao Azure Administrator Certification (AZ-104)**

- Visão geral do papel do Administrador do Azure
- Conceitos fundamentais de nuvem, modelos de serviço (IaaS, PaaS, SaaS)
- Introdução ao portal do Azure e principais áreas de gerenciamento

# 2. Gerenciamento de Identidade e Acesso

# Microsoft Entra ID (Azure AD)
- Gerenciamento centralizado de identidades
- Integração com AD local (sincronização via Azure AD Connect)

# Contas de Usuário e Grupo
- Criação de usuários manuais ou por sincronização
- Atribuição de funções administrativas

# Administração de Identidade
- Autenticação multifator (MFA)
- Políticas de senha e segurança

# RBAC (Role-Based Access Control)
- Controle de permissões baseado em funções
- Escopos: grupo de recursos, assinatura ou recurso específico

# 3. Governança e Conformidade

# Assinaturas do Azure
- Escopo de cobrança e organização de recursos
- Vínculo com diretórios e tenants

# Azure Policy
- Aplicação de regras e restrições (ex: bloquear tipos de VM)
- Compliance automático de recursos existentes

# Governança com RBAC + Policy
- Princípio do menor privilégio
- Padronização e conformidade com normas internas

# 4. Gerenciamento de Recursos no Azure

# Ferramentas
- Portal do Azure
- Azure CLI
- Azure PowerShell
- Azure Resource Graph

# Modelos ARM (Azure Resource Manager)
- Definição de infraestrutura como código (IaC)
- Arquivos JSON para implantar recursos automaticamente

# Administração
- Tags para organização
- Bloqueios (Locks) para proteger recursos de alterações

# 5. Redes Virtuais no Azure

# VNets
- Segmentação da rede em sub-redes
- Isolamento e comunicação entre redes

# Grupos de Segurança de Rede (NSG)
- Controle de tráfego de entrada e saída
- Regras por IP, porta e protocolo

# DNS no Azure
- DNS interno e customizado
- Zonas privadas e públicas

# Emparelhamento de VNet
- Comunicação entre redes distintas no mesmo ou em diferentes tenants

### Pontos de Extremidade e Roteamento
- Private Endpoints
- Service Endpoints
- UDRs (User Defined Routes)

## 6. Armazenamento no Azure

# Contas de Armazenamento
- Tipos: Standard, Premium, BlobStorage, FileStorage

# Blobs
- Armazenamento de objetos
- Containers e níveis de acesso

# Segurança
- Chaves de acesso e SAS (Shared Access Signatures)
- Firewalls e regras de rede

# Arquivos do Azure
- Compartilhamento SMB compatível com Windows
- Montagem em VMs e servidores on-premises

# 7. Máquinas Virtuais e Alta Disponibilidade

# Criação de VMs
- Seleção de imagem, tamanho, disco e rede
- Tipos de disco (Standard HDD, SSD, Premium SSD)

# Disponibilidade
- Conjuntos de disponibilidade (Availability Sets)
- Zonas de disponibilidade

# Load Balancer
- Distribuição de tráfego entre VMs
- Regras de backend e probes de integridade

# Application Gateway
- Balanceamento de carga com inspeção SSL
- WAF (Firewall de Aplicativo Web) integrado

# Observador de Rede (Network Watcher)
- Diagnóstico e monitoramento de conectividade
- Captura de pacotes e logs de fluxo

# 8. Conclusão e Dicas Finais

- Use sempre **nomenclaturas padronizadas** nos recursos
- Aproveite **templates ARM** para padronizar ambientes
- Utilize **tags e políticas** para governança e compliance
- Explore **o modo gratuito (Free Tier)** para testes no Azure
- Treine comandos com Azure CLI para agilidade e automação
- Estude com base em cenários reais e **simulados AZ-104**

# 🔗 Recursos Complementares

- [Microsoft Learn - AZ-104](https://learn.microsoft.com/pt-br/certifications/azure-administrator/)
- [Portal do Azure](https://portal.azure.com)
- [Documentação oficial do Azure](https://learn.microsoft.com/pt-br/azure/)
- [Guia de Markdown no GitHub](https://guides.github.com/features/mastering-markdown/)
- [Azure CLI Docs](https://learn.microsoft.com/pt-br/cli/azure/)

📌 Jorge Daniel Halmenschlager  
📅 29 de Junho de 2025
🎓 Microsoft - Azure Administrator Certification (AZ-104)
