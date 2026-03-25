## GRC - Access Review Policy

Projeto simulado de Governança, Risco e Compliance (GRC) focado na implementação de um processo de revisão periódica de acessos, alinhado à ISO/IEC 27001, com geração de evidências e documentação auditável.

### Sobre o Projeto

Este repositório demonstra, de forma prática, como estruturar um processo de governança de identidade e acesso, garantindo que permissões sejam periodicamente revisadas, aderentes às funções dos usuários e alinhadas ao princípio do menor privilégio.

O projeto simula um ambiente corporativo real, contemplando definição de política, execução do processo, geração de evidências e rastreabilidade para fins de auditoria.

---

### Objetivo

Estabelecer diretrizes para garantir que os acessos aos sistemas corporativos sejam revisados periodicamente, assegurando conformidade, rastreabilidade e mitigação de riscos de segurança.

### Cenário Simulado

Empresa fictícia: **TechCorp Ltda**  
Ambiente corporativo com aproximadamente 150 usuários, distribuídos entre áreas administrativa, financeira e operacional.

Sistemas considerados:
- Microsoft 365 (Exchange Online, SharePoint)
- Active Directory
- Sistema de inventário e chamados (GLPI)

### Frameworks e Controles Aplicados

Este projeto foi estruturado com base nas seguintes boas práticas e frameworks:

- ISO/IEC 27001 (Controles de Acesso)
- ISO/IEC 27002 (Boas práticas de segurança da informação)
- Princípio do menor privilégio (Least Privilege)
- Segregação de funções (SoD – Segregation of Duties)

Controles considerados:

- A.9.2.5 – Review of user access rights  
- A.9.1.2 – Access to networks and network services  
- A.6.1.2 – Segregation of duties  

Para mais detalhes sobre os controles aplicados, incluindo explicações e exemplos práticos, consulte a documentação disponível em `/docs`.

---

### Processo de Revisão de Acessos

O processo definido neste projeto segue as etapas abaixo:

1. Extração de acessos dos sistemas.
2. Consolidação das permissões em base estruturada de análise.
3. Validação junto aos gestores responsáveis.
4. Identificação de acessos indevidos, excessivos ou incompatíveis com a função.
5. Definição de ações corretivas.
6. Execução dos ajustes de acesso.
7. Registro de evidências para auditoria.
