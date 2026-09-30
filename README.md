# João Victor Beato

Delivery Lead | Salesforce, Data Cloud & Martech | Braze & Insider One

Lidero projetos de CRM e martech no ecossistema Salesforce (Sales, Service, Marketing Cloud, Data Cloud, Loyalty, Agentforce), Braze e Insider One, do discovery ao hypercare. Respondo pela gestão da entrega e pela decisão técnica: modelo de dados, integrações e automação.

Trabalho na DDGroup, consultoria parceira Salesforce, Braze e Insider, com clientes de varejo, mercado de capitais, fintech, wealthtech, esporte e educação. Entre os projetos que desenhei está a arquitetura de fidelidade do Hirota Food, case publicado no [blog da Salesforce Brasil](https://www.salesforce.com/br/blog/transformacao-digital-hirota/).

### Como eu entrego

- O repositório é a fonte da verdade: toda mudança feita na org volta ao controle de versão na mesma entrega, para que o próximo deploy não desfaça o que estava certo.
- O Salesforce Code Analyzer é executado no GitHub Actions a cada pull request e barra violação crítica e violação alta nova. Antes de cada entrega, o scan local inclui também as regras de segurança do Graph Engine.
- Os testes de Apex são executados com o usuário do perfil que vai usar a funcionalidade, e não com o administrador, para que a falta de permissão apareça no teste e não na produção.
- A subida para produção é validada na própria produção antes da janela de deploy.
- O QA funcional percorre cada jornada de ponta a ponta, e cada decisão de arquitetura fica registrada em ADR.
- Agentes de IA (Claude) aceleram documentação, QA e revisão de código, com revisão técnica obrigatória e governança sobre os dados do cliente.

### Stack

- Salesforce: Apex, LWC, Flow, SOQL, Data Cloud, Marketing Cloud, Loyalty Management, Service Cloud com Messaging, Agentforce, Salesforce CLI e Code Analyzer.
- Martech: Braze, Insider One, jornadas multicanal (e-mail, SMS, push e WhatsApp), aquecimento de IP e gestão de consentimento.
- Integração: APIs REST e Bulk, OAuth com JWT, MuleSoft e AWS.

### Código aberto

- [salesforce-delivery-guardrails](https://github.com/jvbeat/salesforce-delivery-guardrails): hook do Claude Code que bloqueia comando do Salesforce CLI sem org de destino e gate do Code Analyzer para GitHub Actions, com testes automatizados.
- [forcedotcom/sf-skills #355](https://github.com/forcedotcom/sf-skills/issues/355): medição do custo do gate de skills do plugin salesforce-development e proposta de persistir o despacho por sessão.

### Formação e certificações

Formação em Engenharia de Software pela UNINTER. Braze Marketer Certification e Lean Six Sigma Yellow Belt.

### Contato

[LinkedIn](https://www.linkedin.com/in/joaovictorbeatoribeiro)

<details>
<summary>In English</summary>

I lead CRM and martech projects across the Salesforce ecosystem (Sales, Service, Marketing Cloud, Data Cloud, Loyalty, Agentforce), Braze and Insider One, from discovery to hypercare, owning both delivery management and technical decisions: data modeling, integrations and automation.

I work at DDGroup, a Salesforce, Braze and Insider partner consultancy, with clients in retail, capital markets, fintech, wealthtech, sports and education. Among the solutions I designed is Hirota Food's loyalty architecture, published on [Salesforce Brazil's blog](https://www.salesforce.com/br/blog/transformacao-digital-hirota/).

How I deliver: the repository is the source of truth, and every change made in the org goes back to version control in the same delivery. Salesforce Code Analyzer runs in GitHub Actions on every pull request, blocking critical and new high violations, and the local scan before every delivery adds the Graph Engine security rules. Apex tests run as the profile user who will use the feature, not as an admin. Production deployments are validated in production before the release window. Functional QA walks each journey end to end, and architecture decisions are recorded as ADRs. AI agents (Claude) speed up documentation, QA and code review, under mandatory technical review and client data governance.

Open source: [salesforce-delivery-guardrails](https://github.com/jvbeat/salesforce-delivery-guardrails), a Claude Code hook that blocks Salesforce CLI commands without a target org, plus a Code Analyzer gate for GitHub Actions.

</details>
