# Cloud Security – Ferramentas e Recursos

Neste repositório você encontrará uma curadoria de links e recursos recomendados para se manter atualizado sobre **tendências, boas práticas e ferramentas de segurança em nuvem (Cloud Security)**.

O objetivo principal desta seleção é reunir **ferramentas ativamente mantidas e atualizadas**, evitando projetos obsoletos. Em segurança em nuvem, é essencial acompanhar continuamente as melhores práticas e a evolução do cenário de ameaças.

---

## Cloud Security Posture Management (CSPM)

| Ferramenta | Descrição |
| --- | --- |
| [CloudSploit](https://github.com/aquasecurity/cloudsploit) | Projeto open source da Aqua para detecção de riscos de segurança em contas de infraestrutura em nuvem, incluindo AWS, Microsoft Azure, GCP, OCI e GitHub |
| [Cartography](https://github.com/lyft/cartography) | Ferramenta em Python que consolida ativos de infraestrutura e seus relacionamentos em uma visualização baseada em grafos |
| [Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian/) | Engine de regras para segurança, governança e otimização de custos em nuvem, utilizando uma DSL em YAML para consultar, filtrar e executar ações em recursos |
| [CloudQuery](https://github.com/cloudquery/cloudquery) | Solução open source de CSPM para monitorar e aplicar políticas de segurança em ambientes AWS, GCP, Azure e outros |
| [ElectricEye](https://github.com/jonrau1/ElectricEye) | Ferramenta CLI em Python para gerenciamento de ativos, postura de segurança e monitoramento de superfície de ataque em ambientes multi-cloud e SaaS |
| [Magpie](https://github.com/openraven/magpie) | CSPM com foco em análise de segurança para stacks modernos em nuvem e ameaças emergentes como ransomware em cloud e ataques à cadeia de suprimentos |
| [Prowler](https://github.com/prowler-cloud/prowler) | Ferramenta open source para avaliações de segurança, auditorias, resposta a incidentes, compliance, monitoramento contínuo, hardening e prontidão forense em AWS, Azure, GCP e Kubernetes |
| [ScoutSuite](https://github.com/nccgroup/ScoutSuite) | Ferramenta de auditoria de segurança multi-cloud |
| [Steampipe AWS Compliance](https://github.com/turbot/steampipe-mod-aws-compliance) | Controles individuais ou benchmarks completos de compliance (CIS, PCI, NIST, HIPAA, entre outros) para contas AWS |
| [Komiser](https://github.com/tailwarden/komiser) | Inspetor open source de ambientes em nuvem |
| [ZeusCloud](https://github.com/Zeus-Labs/ZeusCloud) | Descoberta, priorização e remediação de riscos em ambientes cloud |
| [Azure Resource Configuration Scanner](https://github.com/mertyeter/az-resource-config-scanner) | Script em PowerShell para escanear e coletar configurações relacionadas à segurança em recursos Azure |
| [YES3 Scanner](https://github.com/FogSecurity/yes3-scanner) | Scanner de segurança para Amazon S3 com foco em controle de acesso e proteção contra ransomware |
| [Finders Keypers](https://github.com/FogSecurity/finders-keypers) | Ferramenta para análise de uso de chaves AWS KMS e avaliação de blast radius |

---

## Cloud Pentesting Tools

| Ferramenta | Descrição |
| --- | --- |
| [CloudFox](https://github.com/BishopFox/cloudfox) | Automação de reconhecimento e consciência situacional para testes de penetração em ambientes cloud |
| [hackingthe.cloud](https://github.com/Hacking-the-Cloud/hackingthe.cloud) | Enciclopédia de conhecimento ofensivo e defensivo em tecnologias cloud-native |
| [cloud_enum](https://github.com/initstring/cloud_enum) | Ferramenta OSINT multi-cloud para enumeração de recursos públicos em AWS, Azure e Google Cloud |
| [Pacu](https://github.com/RhinoSecurityLabs/pacu) | Framework de exploração AWS voltado para testes de segurança em ambientes Amazon Web Services |
| [CloudBrute](https://github.com/0xsha/cloudbrute) | Ferramenta de enumeração de recursos em nuvem |
| [aws-whoami-golang](https://github.com/benkehoe/aws-whoami-golang) | Ferramenta para identificar a conta e a identidade AWS em uso |
| [cognito-scanner](https://github.com/padok-team/cognito-scanner) | Script para exploração de ataques em Amazon Cognito, como Account Oracle e Privilege Escalation |
| [EscalateGPT](https://github.com/padok-team/cognito-scanner) | Ferramenta baseada em IA para descoberta de oportunidades de escalonamento de privilégios em configurações IAM da AWS |
| [surf](https://github.com/assetnote/surf) | Exploração e escalonamento de vulnerabilidades SSRF em ambientes cloud modernos |
| [Halberd](https://github.com/vectra-ai-research/Halberd) | Ferramenta de ataque multi-cloud para avaliação proativa de defesas em Entra ID, M365, Azure e AWS |
| [CloudShovel](https://github.com/saw-your-packet/CloudShovel) | Scanner de AMIs públicas ou privadas em busca de arquivos sensíveis e segredos |
| [Stratus Red Team](https://github.com/DataDog/stratus-red-team/) | Emulação granular de técnicas ofensivas em nuvem, inspirado no Atomic Red Team |
| [ROADtools](https://github.com/dirkjanm/ROADtools) | Framework para interação com Azure AD, incluindo enumeração e troca de tokens |
| [BucketShield](https://github.com/Permiso-io-tools/Bucket-Shield) | Ferramenta open source para simular e detectar ações que possam interromper o fluxo de logs do AWS CloudTrail |
| [CloudPEASS](https://github.com/carlospolop/CloudPEASS) | Conjunto de scripts para descoberta de permissões e privilege escalation em AWS, Azure e GCP |
| [findmytakeover](https://github.com/anirudhbiyani/findmytakeover) | Detecção de domínios pendentes (dangling domains) em ambientes multi-cloud |

---

## Cloud Pentesting Labs

| Laboratório | Descrição |
| --- | --- |
| [AWSGoat](https://github.com/ine-labs/AWSGoat) | Infraestrutura AWS intencionalmente vulnerável para treinamento |
| [Big IAM Challenge (Wiz)](https://bigiamchallenge.com/challenge/1) | Desafios práticos para testar habilidades em segurança de IAM |
| [iam-vulnerable](https://github.com/BishopFox/iam-vulnerable) | Playground de privilege escalation em IAM utilizando Terraform |
| [Cloud Hunting Games](https://www.cloudhuntinggames.com) | CTF focado em Incident Response em ambientes cloud |
| [cloudbreachsim](https://cloudbreachsim.senayakut.com/) | Simulador interativo de cenários de ataque e defesa em nuvem |

---

## Cloud Asset Management & Activity Monitoring

| Ferramenta | Descrição |
| --- | --- |
| [aws-list-resources](https://github.com/welldone-cloud/aws-list-resources) | Listagem de recursos AWS por conta e região |
| [aws-summarize-account-activity](https://github.com/welldone-cloud/aws-summarize-account-activity) | Análise de dados do CloudTrail para resumir atividades recentes de identidades IAM |
| [wut.dev](https://wut.dev/) | Navegador client-side para AWS Organizations e SCPs |
| [Cloud Console Cartographer](https://github.com/Permiso-io-tools/CloudConsoleCartographer) | Framework para consolidação e visualização de eventos em ambientes cloud |
| [threat-composer](https://github.com/awslabs/threat-composer) | Ferramenta simples para threat modeling |
| [cloudtail](https://github.com/Permiso-io-tools/cloudtail) | Retenção e pesquisa de logs cloud de longo prazo |
| [RansomWhen](https://github.com/Permiso-io-tools/RansomWhen) | Detecção de riscos de ransomware em S3 utilizando KMS |
| [TrailAlerts](https://github.com/adanalvarez/TrailAlerts) | Ferramenta serverless nativa da AWS para detecção de eventos baseada em regras |
| [iam-lens](https://github.com/cloud-copilot/iam-lens) | Visibilidade de permissões IAM em contas e organizações AWS |

---

## Infrastructure as Code (IaC) Security

| Ferramenta | Descrição |
| --- | --- |
| [Checkov](https://github.com/bridgecrewio/checkov) | Prevenção de misconfigurations e detecção de vulnerabilidades em IaC durante o build |
| [cdk-nag](https://github.com/cdklabs/cdk-nag) | Validação de boas práticas em aplicações AWS CDK |
| [KICS](https://github.com/Checkmarx/kics) | Scanner de vulnerabilidades, compliance e misconfigurations em infraestrutura como código |
| [Terrascan](https://github.com/tenable/terrascan) | Detecção de violações de segurança e compliance em IaC antes do provisionamento |
| [tfsec](https://github.com/aquasecurity/tfsec) | Scanner de segurança para código Terraform |
| [tfprovidercheck](https://github.com/suzuki-shunsuke/tfprovidercheck) | CLI para prevenção de execução de providers Terraform maliciosos |
| [terraform-iam-policy-validator]() | Ferramenta de linha de comando para validação de políticas IAM definidas em templates Terraform |

---

## Contribuições

Contribuições são bem-vindas.

Caso conheça ferramentas relevantes, ativamente mantidas e alinhadas às boas práticas de Cloud Security, sinta-se à vontade para abrir um Pull Request e contribuir com este repositório.
