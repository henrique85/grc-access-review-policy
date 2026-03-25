# grc-access-review-policy
Projeto simulado de GRC com política de revisão de acessos baseada na ISO 27001, incluindo governança, evidências e documentação auditável.

## GRC - Access Review Policy

### Sobre o Projeto

Este repositório apresenta um projeto simulado de Governança, Risco e Compliance (GRC), com foco na implementação de uma Política de Revisão Periódica de Acessos.

O objetivo é demonstrar, de forma prática, como estruturar processos de governança de identidade e acesso, alinhados às boas práticas da ISO/IEC 27001 e ao princípio do menor privilégio.

---

### Objetivo

Estabelecer diretrizes para garantir que os acessos aos sistemas corporativos sejam revisados periodicamente, assegurando conformidade, rastreabilidade e mitigação de riscos de segurança.

---

### Cenário Simulado

Empresa fictícia: **TechCorp Ltda**  
Ambiente com aproximadamente 150 usuários  

Sistemas considerados:
- Microsoft 365 (Exchange Online, SharePoint)
- Active Directory
- Sistema de inventário/chamados (GLPI)

---

### Frameworks e Controles Aplicados

Este projeto foi estruturado com base nas seguintes referências:

- ISO/IEC 27001 (Controles de Acesso)
- ISO/IEC 27002 (Boas práticas de segurança da informação)
- Princípio do menor privilégio (Least Privilege)
- Segregação de funções (SoD – Segregation of Duties)

Controles considerados:

- A.9.2.5 – Review of user access rights  
- A.9.1.2 – Access to networks and network services  
- A.6.1.2 – Segregation of duties  

---

### Processo de Revisão de Acessos

O processo definido neste projeto segue as etapas abaixo:

1. Extração de acessos dos sistemas.
2. Consolidação das permissões em base de análise.
3. Validação junto aos gestores responsáveis.
4. Identificação de acessos indevidos ou excessivos.
5. Definição de ações corretivas.
6. Execução dos ajustes de acesso.
7. Registro de evidências para auditoria.
