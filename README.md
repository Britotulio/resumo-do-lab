# Resumo do Lab - Armazenamento em Nuvem

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO (Digital Innovation One), com foco em computação em nuvem e armazenamento.

---

## Modelos de Nuvem

### Nuvem Pública
Recursos de TI são disponibilizados por provedores terceirizados via internet e compartilhados entre múltiplos clientes. Principais provedores: **Microsoft Azure**, **Amazon Web Services (AWS)** e **Google Cloud Platform (GCP)**.

- Sem necessidade de gerenciar infraestrutura física
- Cobrança baseada no consumo real
- Escalabilidade quase ilimitada

### Nuvem Privada
Infraestrutura dedicada exclusivamente a uma organização, podendo ser hospedada localmente (on-premises) ou por um provedor especializado.

- Maior controle sobre dados e segurança
- Personalização total do ambiente
- Indicada para setores com regulamentações rígidas (saúde, financeiro, governo)

### Nuvem Híbrida
Combina nuvem pública e privada, permitindo que dados e aplicações transitem entre os dois ambientes de forma integrada.

- Flexibilidade para manter dados sensíveis na nuvem privada
- Aproveita a escalabilidade da nuvem pública para picos de demanda
- Estratégia cada vez mais adotada por grandes empresas

---

## Benefícios do Armazenamento em Nuvem

| Benefício | Descrição |
|-----------|-----------|
| **Escalabilidade** | Aumento ou redução de recursos conforme a demanda, sem interrupções |
| **Economia** | Modelo pay-as-you-go elimina gastos com infraestrutura ociosa |
| **Disponibilidade** | Alta disponibilidade (SLAs de até 99,99%) com redundância geográfica |
| **Segurança** | Criptografia em repouso e em trânsito, firewalls e auditorias contínuas |
| **Acessibilidade** | Dados acessíveis de qualquer lugar com conexão à internet |
| **Backup automático** | Replicação e recuperação de desastres integradas |
| **Colaboração** | Compartilhamento e edição simultânea de arquivos entre equipes |

---

## Tipos de Armazenamento em Nuvem

### Armazenamento de Objetos (Object Storage)
Ideal para grandes volumes de dados não estruturados como imagens, vídeos e backups.
- Exemplos: Azure Blob Storage, Amazon S3, Google Cloud Storage

### Armazenamento de Arquivos (File Storage)
Sistema de arquivos gerenciado, acessível via protocolos NFS ou SMB.
- Exemplos: Azure Files, Amazon EFS

### Armazenamento em Bloco (Block Storage)
Alta performance para bancos de dados e sistemas operacionais.
- Exemplos: Azure Disk Storage, Amazon EBS

---

## Métodos e Modos de Acesso

- **Portal Web**: Interface gráfica para gerenciamento visual dos recursos
- **CLI (Command Line Interface)**: Comandos via terminal para automação e scripts
- **SDK e APIs REST**: Integração programática com aplicações
- **RBAC (Role-Based Access Control)**: Controle de acesso granular por funções
- **Chaves e Tokens**: Autenticação segura via SAS tokens, OAuth e chaves de API
- **VPN / ExpressRoute**: Conexão privada e segura entre ambientes on-premises e a nuvem

---

## Segurança na Nuvem

- **Criptografia**: Dados protegidos em repouso (AES-256) e em trânsito (TLS)
- **Identidade e Acesso**: Multi-fator (MFA), Active Directory integrado
- **Conformidade**: Certificações como ISO 27001, SOC 2, LGPD, GDPR
- **Monitoramento**: Logs de auditoria e alertas em tempo real
- **Políticas de Retenção**: Controle do ciclo de vida dos dados

---

## Evolução Tecnológica e Impacto nos Negócios

A computação em nuvem representa uma das maiores transformações da TI moderna:

- **Democratização da tecnologia**: Pequenas empresas acessam a mesma infraestrutura que grandes corporações
- **Redução do CAPEX**: Elimina investimentos elevados em hardware e data centers próprios
- **Agilidade**: Novos serviços podem ser provisionados em minutos
- **Inovação acelerada**: Serviços gerenciados de IA, machine learning e big data disponíveis sob demanda
- **Sustentabilidade**: Data centers em nuvem tendem a ser mais eficientes energeticamente que infraestruturas locais

---

## Conclusão

O lab reforçou como o armazenamento em nuvem vai muito além de simplesmente guardar arquivos. É uma plataforma estratégica que impulsiona a transformação digital, reduz custos operacionais e oferece ferramentas para que empresas de qualquer porte inovem com velocidade e segurança.
