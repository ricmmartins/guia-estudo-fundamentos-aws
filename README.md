# 📗 Guia de estudo para o exame AWS Certified Cloud Practitioner

Este guia tem por objetivo fornecer uma lista de materiais pré-selecionados para ajudar qualquer pessoa iniciando na carreira de computação em nuvem e/ou descobrindo a AWS a estar pronta para o exame AWS Certified Cloud Practitioner

*Última atualização em 15 de Maio de 2023*

> **_NOTA:_** O conteúdo de alguns links está em inglês por não possuir uma tradução criada pela AWS em Português, principalmente os Whitpapers e conteúdos de alguns blogs da AWS.

## 📝 Habilidades medidas - [Obtido no link oficial](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)

### 💡 Conceitos de nuvem (26%)

#### Defina a Nuvem AWS e sua proposta de valor
* Definir os benefícios da nuvem AWS, incluindo
   * Segurança
     * [AWS Cloud Security](https://aws.amazon.com/pt/security/)
     * [Segurança, Identidade e Conformidade na AWS](https://aws.amazon.com/pt/products/security/)
     * [Whitepaper de segurança e conformidade](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/security-and-compliance.html)
   * Confiabilidade
     * [Definição de confiabilidade](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.pillar.reliability.en.html)
   * Alta disponibilidade
     * [Alta disponibilidade e escalabilidade na AWS](https://docs.aws.amazon.com/whitepapers/latest/real-time-communication-on-aws/high-availability-and-scalability-on-aws.html)
   * Elasticidade
     * [Definição de Elasticidade](https://wa.aws.amazon.com/wat.concept.elasticity.en.html)
   * Agilidade
     * [O que é Cloud Computing - Procure Agilidade](https://aws.amazon.com/pt/what-is-cloud-computing/)
   * Preços pré-pagos
     * [Como funciona a precificação da AWS?](https://aws.amazon.com/pt/pricing/?aws-products-pricing.sort-by=item.additionalFields.productNameLowercase&aws-products-pricing.sort-order=asc&awsf.Free %20Tier%20Type=*all&awsf.tech-category=*all#)
   * Escalabilidade
     * [Definição de escalabilidade](https://wa.aws.amazon.com/wat.concept.scalability.en.html)
   * Alcance global
     * [AWS Global Infrastructure](https://aws.amazon.com/pt/about-aws/global-infrastructure/?pg=cloudessentials)
   * Economia de escala
     * [Seis vantagens da computação em nuvem](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html)
     * [Introduction to Cloud Economics](https://d1.awsstatic.com/whitepapers/introduction-to-aws-cloud-economics-final.pdf)
* Explicar como a nuvem AWS permite que os usuários se concentrem no valor comercial
     * [Valor comercial na AWS](https://aws.amazon.com/pt/executive-insights/content/business-value-on-aws/)
     * [Aclcançando valor empresarial com a AWS](https://aws.amazon.com/pt/executive-insights/content/realizing-business-value-with-aws/)
* Deslocar recursos técnicos para atividades geradoras de receita, em vez de gerenciar
a infraestrutura
     * [Centro de Informações sobre Aspectos Econômicos da Nuvem](https://aws.amazon.com/pt/economics/)
     * [O que é IaaS (Infraestrutura como serviço)?](https://aws.amazon.com/pt/what-is/iaas/)

#### Identificar aspectos da economia da Nuvem AWS
* Definir itens que fariam parte de uma proposta de custo total de propriedade (TCO)
   * Compreender o papel das despesas operacionais (OpEx)
   * Compreender o papel das despesas de capital (CapEx)
   * Entenda os custos de mão de obra associados às operações locais (on-premises)
   * Entenda o impacto dos custos de licenciamento de software ao migrar para a nuvem

> **_NOTA:_** Todos os itens acima são abordados neste e-book: [AWS Cloud Economics](https://pages.awscloud.com/rs/112-TZM-766/images/Cloud%20Economics%20Ebook_October%202018.pdf)

* Identifique quais operações reduzirão custos migrando para a nuvem
   * Infraestrutura do tamanho certo
     * [Dicas para dimensionamento correto](https://docs.aws.amazon.com/whitepapers/latest/cost-optimization-right-sizing/tips-for-right-sizing-your-workloads.html)
     * [Redimensionar antes de migrar](https://docs.aws.amazon.com/whitepapers/latest/cost-optimization-right-sizing/right-size-before-migrating.html)
   * Benefícios da automação
     * [Avalie os benefícios de custo da automação](https://docs.aws.amazon.com/wellarchitected/latest/sap-lens/best-practice-17-7.html)
   * Reduza o escopo de conformidade (por exemplo, relatórios)
   * Serviços gerenciados (por exemplo, RDS, ECS, EKS, DynamoDB)
     * [10 coisas que você pode fazer hoje para reduzir os custos da AWS](https://aws.amazon.com/blogs/compute/10-things-you-can-do-today-to-reduce-aws-costs/)

#### Explicar os diferentes princípios de design de arquitetura de nuvem
* Explique os princípios de design
   * Projetando para falhas
   * Desacoplar componentes versus arquitetura monolítica
   * Implemente elasticidade na nuvem versus no local (on-premises)
   * Pense em paralelismo

> **_NOTE:_** Todos os itens acima são abordados neste e-book: [Architecting in the Cloud](http://aws001.s3.amazonaws.com/trailhead/TrailHead_ArchitectingInTheCloud.pdf)

### 💡 Segurança e Conformidade (25%)

#### Defina o modelo de responsabilidade compartilhada da AWS
* Reconhecer os elementos do Modelo de Responsabilidade Compartilhada
* Descrever a responsabilidade do cliente na AWS
   * Descreva como as responsabilidades do cliente podem mudar dependendo do serviço usado
(por exemplo, com RDS, Lambda ou EC2)
* Descrever as responsabilidades da AWS

> **_NOTA:_** Todos os itens acima são abordados neste link: [Modelo de Responsabilidade Compartilhada](https://aws.amazon.com/pt/compliance/shared-responsibility-model/)

#### Defina os conceitos de segurança e conformidade da Nuvem AWS
* Identifique onde encontrar informações de conformidade da AWS
   * Locais de listas de controles de conformidade disponíveis reconhecidos (por exemplo, HIPPA,
SOCs)
     * [Perguntas frequentes sobre conformidade](https://aws.amazon.com/pt/compliance/faq/)
   * Reconhecer que os requisitos de conformidade variam entre os serviços da AWS
     * [Serviços da AWS no escopo do programa de conformidade](https://aws.amazon.com/compliance/services-in-scope/SOC/)
     * [Introdução à segurança da AWS - seção de conformidade](https://docs.aws.amazon.com/whitepapers/latest/introduction-aws-security/compliance.html)
     * [Introduction to AWS Security - PDF Whitepaper](https://d1.awsstatic.com/whitepapers/Security/Intro_to_AWS_Security.pdf)
     * [E-book de Risco e Conformidade da AWS](https://docs.aws.amazon.com/pdfs/whitepapers/latest/aws-risk-and-compliance/aws-risk-and-compliance.pdf)
* Em alto nível, descreva como os clientes obtêm conformidade na AWS
   * Identifique diferentes opções de criptografia na AWS (por exemplo, em trânsito, em repouso)
     * [Criptografia de dados](https://docs.aws.amazon.com/whitepapers/latest/introduction-aws-security/data-encryption.html)
     * [Criptografando dados em repouso e em trânsito](https://docs.aws.amazon.com/whitepapers/latest/logical-separation/encrypting-data-at-rest-and-in-transit.html)
* Descrever quem habilita a criptografia na AWS para um determinado serviço
   * [A importância da criptografia e como a AWS pode ajudar](https://aws.amazon.com/blogs/security/importance-of-encryption-and-how-aws-can-help/)
   * [Três perguntas comuns sobre criptografia em nuvem e suas respostas na AWS](https://aws.amazon.com/blogs/security/three-common-cloud-encryption-questions-and-their-answers-on-aws/)
* Reconhecer que existem serviços que ajudarão na auditoria e relatórios
   * [AWS Config](https://aws.amazon.com/pt/config/)
   * [AWS CloudTrail](https://aws.amazon.com/pt/cloudtrail/)
   * [AWS Audit Manager](https://aws.amazon.com/pt/audit-manager/)
   * [AWS Artifact](https://aws.amazon.com/pt/artifact/)
   * Reconhecer que existem logs para auditoria e monitoramento (não precisa entender o
Histórico)
     * [Monitoramento, auditoria e registro de registro de eventos](https://docs.aws.amazon.com/whitepapers/latest/architecting-hipaa-security-and-compliance-on-amazon-eks/event-logging-monitoring-auditing-and-logging.html)
   * Definir Amazon CloudWatch, AWS Config e AWS CloudTrail
     * [O que é Amazon CloudWatch?](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)
     * [O que é AWS Config?](https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html)
     * [O que é AWS CloudTrail?](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-user-guide.html)
* Explique o conceito de acesso menos privilegiado
   * [Conceder privilégio mínimo](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html#grant-least-priv)

   #### Identifique os recursos de gerenciamento de acesso da AWS
* Entenda o propósito do gerenciamento de usuários e identidades
   * [Quando devo usar o IAM?](https://docs.aws.amazon.com/IAM/latest/UserGuide/when-to-use-iam.html)
   * [Visão geral do gerenciamento de identidade da AWS: usuários](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction_identity-management.html)
   * Chaves de acesso e políticas de senha (rotação, complexidade)
     * [Gerenciando chaves de acesso para usuários do IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html)
   * Autenticação multifator (MFA)
     * [Autenticação multifator (MFA) para IAM](https://aws.amazon.com/pt/iam/features/mfa/)
   * AWS Identity and Access Management (IAM)
     * Grupos/usuários
       * [Usuários do IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users.html)
       * [Grupos de usuários do IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_groups.html)
     * Funções
       * [funções do IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles.html)
     * Políticas, políticas gerenciadas em comparação com políticas personalizadas
       * [Políticas e permissões no IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html)
       * [Visão geral do gerenciamento de acesso: permissões e políticas](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction_access-management.html)
       * [O que são políticas gerenciadas pela AWS?](https://docs.aws.amazon.com/aws-managed-policy/latest/reference/about-managed-policy-reference.html)
       * [Criando políticas IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_create.html)
   * Tarefas que requerem o uso de contas root
     * [Tarefas que requerem credenciais de usuário root](https://docs.aws.amazon.com/accounts/latest/reference/root-user-tasks.html)
   * Proteção de contas root
     * [Práticas recomendadas para proteger o usuário root da sua conta](https://docs.aws.amazon.com/accounts/latest/reference/best-practices-root-user.html)

#### Identificar recursos para suporte de segurança
* Reconhecer que existem diferentes recursos de segurança de rede
   * Serviços nativos da AWS (por exemplo, grupos de segurança, Network ACLs, AWS WAF)
     * [Proteção de rede e aplicativos na AWS](https://aws.amazon.com/pt/products/security/network-application-protection/)
   * Produtos de segurança de terceiros do AWS Marketplace
     * [Produtos de segurança no AWS Marketplace](https://docs.aws.amazon.com/whitepapers/latest/introduction-aws-security/security-products-in-aws-marketplace.html)
* Reconhecer que existe documentação e onde encontrá-la (por exemplo, melhores práticas, whitepapers, documentos oficiais)
   * AWS Knowledge Center, Security Center, fórum de segurança e blogs de segurança
     * [AWS Knowledge Center](https://repost.aws/knowledge-center)
     * [AWS Security](https://aws.amazon.com/pt/security/)
     * [Blogs de segurança](https://aws.amazon.com/pt/security/blogs/)
   * Integradores de sistemas parceiros
     * [Blog da rede de parceiros da AWS](https://aws.amazon.com/blogs/apn/)
* Saiba que as verificações de segurança são um componente do AWS Trusted Advisor
   * [Avisador confiável da AWS](https://aws.amazon.com/pt/premiumsupport/technology/trusted-advisor/)
   * [Documentação - Trusted Advisor](https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor.html)
   * [Referência de verificação do AWS Trusted Advisor](https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor-check-reference.html)
   * [Melhores práticas do Amazon Trusted Advisor (verificações)](https://www.amazonaws.cn/en/support/trustedadvisor/best-practices/)

### 💡 Tecnologia (33%)

#### Definir métodos de implantação e operação na Nuvem AWS
* Identificar em alto nível diferentes formas de provisionamento e operação na nuvem AWS
   * Acesso programático, APIs, SDKs, AWS Management Console, CLI, Infraestrutura como
Código
     * [O que é uma API?](https://aws.amazon.com/pt/what-is/api/)
     * [O que é um SDK?](https://aws.amazon.com/pt/what-is/sdk/)
     * [O que é o Console de gerenciamento da AWS?](https://docs.aws.amazon.com/awsconsolehelpdocs/latest/gsg/learn-whats-new.html)
     * [O que é a AWS CLI?](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html)
* Identifique diferentes tipos de modelos de implantação em nuvem
   * Tudo com nuvem/nuvem nativa
     * [O que é Cloud Native?](https://aws.amazon.com/pt/what-is/cloud-native/)
   * Híbrido
     * [O que é nuvem híbrida?](https://aws.amazon.com/pt/what-is/hybrid-cloud/)
   * No local (On-premises)
     * [Definição de "on-premises" nos Modelos de implantação de computação em nuvem"](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/types-of-cloud-computing.html)
* Identificar opções de conectividade
   * VPN
     * [AWS VPN](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/networking-services.html#aws-vpn)
   * AWS Direct Connect
     * [AWS Direct Connect](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/networking-services.html#aws-direct-connect)
   * Internet pública

#### Defina a infraestrutura global da AWS
* Descrever as relações entre regiões, zonas de disponibilidade e pontos de presença
   * [AWS Global Infrastructure](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/global-infrastructure.html)
   * [Regiões e zonas](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html)
* Descrever como obter alta disponibilidade por meio do uso de várias zonas de disponibilidade
   * Lembre-se de que a alta disponibilidade é alcançada usando várias zonas de disponibilidade
     * [Usar várias zonas de disponibilidade](https://docs.aws.amazon.com/whitepapers/latest/real-time-communication-on-aws/use-multiple-availability-zones.html)
   * Reconhecer que as Zonas de Disponibilidade não compartilham pontos únicos de falha
     * [Alta disponibilidade e escalabilidade na AWS](https://docs.aws.amazon.com/whitepapers/latest/real-time-communication-on-aws/high-availability-and-scalability-on-aws.html)
* Descrever quando considerar o uso de várias regiões da AWS
   * Recuperação de desastres/continuidade de negócios
     * [Opções de recuperação de desastres na nuvem](https://docs.aws.amazon.com/whitepapers/latest/disaster-recovery-workloads-on-aws/disaster-recovery-options-in-the-cloud.html)
     * [Plano de continuidade de negócios (BCP)](https://docs.aws.amazon.com/whitepapers/latest/disaster-recovery-workloads-on-aws/business-continuity-plan-bcp.html)
     * [Arquitetura de recuperação de desastres (DR) na AWS, parte I: estratégias de recuperação na nuvem](https://aws.amazon.com/blogs/architecture/disaster-recovery-dr-architecture-on-aws-part-i-strategies-for-recovery-in-the-cloud/)
     * [Arquitetura de recuperação de desastres (DR) na AWS, parte II: backup e restauração com recuperação rápida](https://aws.amazon.com/blogs/architecture/disaster-recovery-dr-architecture-on-aws-part-ii-backup-and-restore-with-rapid-recovery/)
     * [Arquitetura de recuperação de desastres (DR) na AWS, Parte III: Pilot Light e Warm Standby](https://aws.amazon.com/blogs/architecture/disaster-recovery-dr-architecture-on-aws-part-iii-pilot-light-and-warm-standby/)
     * [Arquitetura de recuperação de desastres (DR) na AWS, Parte IV: Multi-site ativo/ativo](https://aws.amazon.com/blogs/architecture/disaster-recovery-dr-architecture-on-aws-part-iv-multi-site-ativo-ativo/)
   * Baixa latência para usuários finais
     * [Como a AWS pode ajudar você a reduzir a latência?](https://aws.amazon.com/pt/what-is/latency/#seo-faq-pairs#how-aws-reduces-latency)
   * Soberania de dados
     * [Compromisso de soberania digital da AWS: controle sem compromisso](https://aws.amazon.com/blogs/security/aws-digital-sovereignty-pledge-control-without-compromise/)
     * [Soberania digital na AWS](https://aws.amazon.com/pt/compliance/digital-sovereignty/)
* Descrever em alto nível os benefícios dos pontos de presença
   *Amazon CloudFront
     * [O que é Amazon CloudFront?](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)
   * Acelerador global da AWS
     * [O que é AWS Global Accelerator?](https://docs.aws.amazon.com/global-accelerator/latest/dg/what-is-global-accelerator.html)

#### Identifique os principais serviços da AWS
* Descrever as categorias de serviços na AWS (computação, armazenamento, rede, banco de dados)
   * [Computação na AWS](https://aws.amazon.com/pt/products/compute/)
   * [Armazenamento na AWS](https://aws.amazon.com/pt/products/storage/)
   * [Bancos de dados na AWS](https://aws.amazon.com/pt/products/databases/)
   * [Rede na AWS](https://aws.amazon.com/pt/products/networking/)
* Identifique os serviços de computação da AWS
   * Reconhecer que existem diferentes famílias de computação
     * [Tipos de instância](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-types.html)
   * Reconhecer os diferentes serviços que fornecem computação (por exemplo, AWS Lambda
comparado ao Amazon Elastic Container Service (Amazon ECS), ou Amazon EC2, etc.)
     * [Serviços de computação](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/compute-services.html)
   * Reconhecer que a elasticidade é alcançada por meio do Auto Scaling
     * [O que é Amazon EC2 Auto Scaling?](https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html)
   * Identificar a finalidade dos balanceadores de carga
     * [O que é balanceamento de carga?](https://aws.amazon.com/pt/what-is/load-balancing/)
* Identifique diferentes serviços de armazenamento da AWS
   * Descrever o Amazon S3
     * [O que é Amazon S3?](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)
   * Descrever Amazon Elastic Block Store (Amazon EBS)
     * [Amazon Elastic Block Store](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEBS.html)
   * Descrever Amazon S3 Glacier
     * [O que é o Amazon S3 Glacier?](https://docs.aws.amazon.com/amazonglacier/latest/dev/introduction.html)
   * Descrever o AWS Snowball
     * [O que é um dispositivo AWS Snowball?](https://docs.aws.amazon.com/snowball/latest/ug/whatissnowball.html)
   * Descrever o Amazon Elastic File System (Amazon EFS)
     * [O que é Amazon Elastic File System?](https://docs.aws.amazon.com/efs/latest/ug/whatisefs.html)
   * Descrever AWS Storage Gateway
     * [AWS Storage Gateway](https://docs.aws.amazon.com/storagegateway/index.html)
* Identificar os serviços de rede da AWS
   * Identificar VPC
     * [O que é Amazon VPC?](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)
   * Identificar grupos de segurança
     * [Controle o tráfego para recursos usando grupos de segurança](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-security-groups.html)
   * Identificar o propósito da Amazon Route 53
     * [O que é Amazon Route 53?](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html)
   * Identificar VPN, AWS Direct Connect
     * [AWS VPN](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/networking-services.html#aws-vpn)
     * [AWS Direct Connect](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/networking-services.html#aws-direct-connect)
* Identifique diferentes serviços de banco de dados da AWS
   * Instale bancos de dados no Amazon EC2 em comparação com bancos de dados gerenciados pela AWS
     * [Escolha entre Amazon EC2 e Amazon RDS](https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-sql-server/comparison.html)
   * Identifique o Amazon RDS
     * [O que é Amazon Relational Database Service (Amazon RDS)?](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)
   * Identifique o Amazon DynamoDB
     * [O que é Amazon DynamoDB?](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)
   * Identifique o Amazon Redshift
     * [O que é Amazon Redshift?](https://docs.aws.amazon.com/redshift/latest/mgmt/welcome.html)

#### Identificar recursos para suporte de tecnologia
* Reconheça que existe documentação (melhores práticas, whitepapers, AWS Knowledge Center,
fóruns, blogs)
   * [Documentação da AWS](https://docs.aws.amazon.com/)
   * [Introdução à AWS](https://aws.amazon.com/pt/getting-started/)
   * [AWS Whitepapers e guias](https://aws.amazon.com/pt/whitepapers/)
   * [Blogs da AWS](https://aws.amazon.com/pt/blogs/)
* Identificar os vários níveis e escopo do suporte da AWS
   * Abuso da AWS
     * [Resposta da AWS a abuso e comprometimento](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/abuse-and-compromise.html)
   * Casos de suporte da AWS
     * [Introdução ao AWS Support](https://docs.aws.amazon.com/awssupport/latest/user/getting-started.html)
   *Suporte premium
     * [Planos de suporte da AWS](https://docs.aws.amazon.com/awssupport/latest/user/aws-support-plans.html)
     * [Compare os planos de suporte da AWS](https://aws.amazon.com/pt/premiumsupport/plans/)
   * Gerentes técnicos de contas
     * [AWS Enterprise Support](https://aws.amazon.com/pt/premiumsupport/plans/enterprise/)

* Reconhecer que existe uma rede de parceiros (mercado, terceiros), incluindo fornecedores independentes de software e integradores de sistemas
* Identificar fontes de assistência técnica e conhecimento da AWS, incluindo serviços profissionais,
arquitetos de soluções, treinamento e certificação, e a Amazon Partner Network
* Identificar os benefícios de usar o AWS Trusted Advisor
   * [AWS Trusted Advisor](https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor.html)

### 💡 Cobrança e preços (16%)

#### Compare e diferencie os vários modelos de definição de preço para AWS (por exemplo, instâncias sob demanda, instâncias reservadas e definição de preço de instância spot)
* Identificar cenários/melhor ajuste para preços de instâncias sob demanda
   * [Preços sob demanda](https://aws.amazon.com/pt/ec2/pricing/on-demand/)
* Identificar cenários/melhor ajuste para preços de instâncias reservadas
   * Descrever a flexibilidade das instâncias reservadas
     * [Precificação de Instâncias Reservadas](https://aws.amazon.com/pt/ec2/pricing/reserved-instances/pricing/)
   * Descrever o comportamento de instâncias reservadas no AWS Organizations
     * [Comportamento de instâncias reservadas em organizações da AWS](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/ri-behavior.html)
* Identificar cenários/melhor ajuste para preços de Instância Spot
   * [Instâncias spot do Amazon EC2](https://aws.amazon.com/pt/ec2/spot/)
#### Reconhecer as várias estruturas de conta em relação ao faturamento e definição de preço da AWS
* Reconhecer que o faturamento consolidado é um recurso do AWS Organizations
   * [Faturamento consolidado para AWS Organizations](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/consolidated-billing.html)
* Identifique como várias contas ajudam na alocação de custos entre departamentos
   * [Noções básicas de alocação de custos que você precisa saber](https://aws.amazon.com/blogs/aws-cloud-financial-management/cost-allocation-basics-that-you-need-to-know/)

#### Identifique os recursos disponíveis para suporte de cobrança
* Identificar maneiras de obter suporte e informações de cobrança
   * Explorador de custos, relatório de custo e uso da AWS, Amazon QuickSight, parceiros terceirizados,
e ferramentas do AWS Marketplace
     * [Analisando seus custos com o AWS Cost Explorer](https://docs.aws.amazon.com/cost-management/latest/userguide/ce-what-is.html)
     * [O que são relatórios de custo e uso da AWS?](https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html)
     * [O que é o Amazon QuickSight?](https://docs.aws.amazon.com/quicksight/latest/user/welcome.html)
   * Abra um caso de suporte de cobrança
     * [Como obter ajuda com o faturamento da AWS](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/billing-get-answers.html)
   * A função do Concierge para clientes do AWS Enterprise Support Plan
     * [AWS Enterprise Support](https://aws.amazon.com/pt/premiumsupport/plans/enterprise/)
* Identifique onde encontrar informações sobre preços nos serviços da AWS
   * Calculadora mensal simples da AWS
     * [Estime seus custos – Calculadora mensal simples da AWS](https://aws.amazon.com/blogs/aws/estimate-your-c/)
   * Páginas de produtos de serviços da AWS
   * API de preços da AWS
     * [Usando a API de lista de preços da AWS](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/price-changes.html)
* Reconhecer que existem alarmes/alertas
   * [Configurando notificações de alterações de preço](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/price-notification.html)
   * [Criando um alarme de cobrança para monitorar suas cobranças estimadas da AWS](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html)
* Identificar como as tags são usadas na alocação de custos
   * [Usando tags de alocação de custos da AWS](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/cost-alloc-tags.html)

## Extras

* [Visão geral do Amazon Web Services](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/introduction.html)
* [AWS Cloud Essentials - Guia de primeiros passos](https://aws.amazon.com/getting-started/cloud-essentials/)
* [AWS Security Essentials - Guia de primeiros passos](https://aws.amazon.com/getting-started/aws-security-essentials/)
* [Fundamentos do AWS Billing and Cost Optimizations - Guia de primeiros passos](https://aws.amazon.com/getting-started/cost-optimization-essentials/)
* [AWS Networking Essentials - Guia de primeiros passos](https://aws.amazon.com/getting-started/aws-networking-essentials/)

## Mostre seu apoio
Dê um ⭐️ no repositório GitHub do projeto se esse conteúdo te ajudou!
