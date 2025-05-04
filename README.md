# Projeto sobre Microsoft Azure: Conceitos e Componentes

## Índice
1. [Introdução ao Azure](#introdução-ao-azure)
2. [Máquinas Virtuais no Azure](#máquinas-virtuais-no-azure)
3. [Contas de Usuários e Gerenciamento de Acesso](#contas-de-usuários-e-gerenciamento-de-acesso)
4. [Modelos de Serviços em Nuvem](#modelos-de-serviços-em-nuvem)
5. [Bancos de Dados no Azure](#bancos-de-dados-no-azure)
6. [Componentes de Arquitetura Azure](#componentes-de-arquitetura-azure)

## Introdução ao Azure
O Microsoft Azure é uma plataforma de computação em nuvem que oferece mais de 200 produtos e serviços para criar, implantar e gerenciar aplicações.

![Azure Portal](https://learn.microsoft.com/pt-br/training/azure-fundamentals/media/azure-portal-65a9a8e3.png)

## Máquinas Virtuais no Azure
As VMs (Máquinas Virtuais) no Azure permitem executar sistemas operacionais e aplicações em um ambiente virtualizado.

**Conceitos-chave:**
- Imagens de VM (Windows, Linux)
- Tamanhos de VM (séries B, D, F, etc.)
- Discos gerenciados
- Conjuntos de disponibilidade
- Zonas de disponibilidade

**Processo de criação:**
1. Selecionar uma imagem do sistema operacional
2. Escolher o tamanho da VM conforme necessidades
3. Configurar rede e segurança
4. Definir opções de armazenamento

![Criação de VM no Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/media/quick-create-portal/create-virtual-machine-portal.png)

## Contas de Usuários e Gerenciamento de Acesso
O Azure Active Directory (Azure AD) é o serviço de identidade da Microsoft na nuvem.

**Recursos principais:**
- Autenticação multifator
- SSO (Single Sign-On)
- RBAC (Controle de Acesso Baseado em Função)
- Identidades gerenciadas

**Melhores práticas:**
- Implementar o princípio do menor privilégio
- Usar grupos em vez de atribuições diretas
- Habilitar MFA para todos os usuários

![Azure AD](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/media/active-directory-how-subscriptions-associated-directory/azure-ad-portal.png)

## Modelos de Serviços em Nuvem

### IaaS (Infraestrutura como Serviço)
**Características:**
- Maior controle sobre a infraestrutura
- Responsabilidade pelo SO, middleware e aplicativos
- Exemplos: Azure VMs, Azure Virtual Network

### PaaS (Plataforma como Serviço)
**Características:**
- Foco no desenvolvimento de aplicações
- Gerenciamento automático de recursos
- Exemplos: Azure App Service, Azure Functions

### SaaS (Software como Serviço)
**Características:**
- Software completo gerenciado pelo provedor
- Acesso via navegador ou API
- Exemplos: Office 365, Dynamics 365

![Modelos de Serviço em Nuvem](https://learn.microsoft.com/pt-br/training/azure-fundamentals/media/iaas-paas-saas-comparison-65796f9b.png)

## Bancos de Dados no Azure
Principais opções:

| Serviço | Tipo | Caso de Uso |
|---------|------|-------------|
| Azure SQL Database | Relacional | Aplicativos tradicionais |
| Cosmos DB | NoSQL | Aplicativos globais escaláveis |
| Azure Database for MySQL | Relacional open-source | Migrações de aplicativos existentes |
| Azure Synapse Analytics | Data Warehouse | Análises em grande escala |

[Azure Database Services](https://azure.microsoft.com/pt-br/pricing/purchase-options/azure-account/search?ef_id=_k_Cj0KCQjw_dbABhC5ARIsAAh2Z-SAPDxHknQcI3_iPt73mNRDBZvWfJLR_Smi4FddlnC-fmw8_V8y34oaAmclEALw_wcB_k_&OCID=AIDcmmzmnb0182_SEM__k_Cj0KCQjw_dbABhC5ARIsAAh2Z-SAPDxHknQcI3_iPt73mNRDBZvWfJLR_Smi4FddlnC-fmw8_V8y34oaAmclEALw_wcB_k_&gad_source=1&gbraid=0AAAAADcJh_vflkDXr7BDV1VhDbLslQKiV&gclid=Cj0KCQjw_dbABhC5ARIsAAh2Z-SAPDxHknQcI3_iPt73mNRDBZvWfJLR_Smi4FddlnC-fmw8_V8y34oaAmclEALw_wcB).


## Componentes de Arquitetura Azure

**Elementos essenciais:**
- **Regiões**: Localizações físicas com data centers
- **Resource Manager**: Serviço de implantação e gerenciamento
- **VNet**: Isolamento e segmentação de rede
- **Load Balancer**: Distribuição de tráfego

**Padrões comuns:**
- Arquitetura hub-spoke
- N-tier applications
- Microsserviços com AKS

[Arquitetura de Referência Azure]

## Próximos Passos
- Explorar o Azure Free Tier para testes
- Certificações Azure (AZ-900, AZ-104)
- Implementar um projeto piloto

## Referências
- [Documentação oficial do Azure](https://learn.microsoft.com/pt-br/azure/)
- [Azure Architecture Center](https://learn.microsoft.com/pt-br/azure/architecture/)
- [Microsoft Learn](https://learn.microsoft.com/pt-br/training/azure/)
