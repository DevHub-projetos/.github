# DevHub

Software sob medida para pequenas e médias empresas, com foco em automação e IA aplicada a atendimento.

---

## Sobre

A DevHub desenvolve sistemas sob demanda para empresas que precisam de algo que as ferramentas de prateleira não entregam — seja porque o processo é específico demais, porque o custo por usuário não fecha, ou porque os dados precisam ficar sob controle de quem opera.

Trabalhamos do levantamento ao deploy: entendimento do problema, arquitetura, implementação, publicação e manutenção.

## Como trabalhamos

**Entender antes de propor.** Todo projeto começa com a leitura do que o cliente realmente precisa, e com as perguntas que mudam a estimativa. Proposta enviada sem essa etapa é chute com aparência de orçamento.

**Justificar cada escolha técnica.** Stack não se escolhe por moda. Cada decisão de arquitetura vem acompanhada do motivo e do que ela custa — inclusive em conta mensal de infraestrutura.

**Entregar por blocos.** Escopo fatiado em fases com aceite formal, começando pela versão que já resolve o problema em produção. O cliente vê valor antes do projeto inteiro terminar.

**Infraestrutura do cliente.** Sempre que faz sentido, o sistema roda em servidor do próprio cliente, com os dados sob o controle dele. Sem aprisionamento em plataforma.

**Ressalvas por escrito.** Dependências externas, limites de escopo e o que entra como aditivo ficam no contrato — não na conversa.

## O que fazemos

- **Sistemas de gestão e back-office** — cadastros, ordens de serviço, contratos, agenda, relatórios e portais de cliente
- **Plataformas de atendimento** — inbox compartilhado, integração oficial com a WhatsApp Cloud API da Meta, atribuição e histórico
- **IA aplicada** — copilotos que sugerem respostas para operadores humanos, e bases de conhecimento com busca semântica (RAG)
- **Automação de processos** — substituição de trabalho manual repetitivo por rotinas confiáveis
- **Aplicações web e e-commerce** — do front à API, com autenticação, controle de acesso e meio de pagamento

## Tecnologias

| Camada | Stack |
|---|---|
| Front-end | Next.js, React, TypeScript, Tailwind CSS |
| Back-end | Node.js, TypeScript, Express |
| Dados | PostgreSQL, pgvector, Prisma, Supabase, Redis |
| IA | OpenAI, RAG com busca vetorial |
| Integrações | WhatsApp Cloud API (Meta), meios de pagamento |
| Infraestrutura | Docker, Nginx, VPS, Let's Encrypt |
| Qualidade | Vitest, Playwright, GitHub Actions |

## Engenharia

Um sistema que o cliente vai operar por anos precisa sustentar mudança. O que praticamos:

- **Controle de acesso por papel**, com a barreira real no banco de dados (Row Level Security), não apenas na interface
- **Testes automatizados** em camadas — unidade, ponta a ponta e regras do próprio banco
- **CI** rodando a cada mudança: tipos, lint, testes e build
- **Deploy automatizado** com ambientes separados de desenvolvimento e produção
- **Segredos fora do código**, com revisão de dependências vulneráveis
- **LGPD** considerada desde o início: exportação de dados do titular, exclusão de conta e política de retenção

## Projetos

Os projetos da DevHub estão hoje em repositórios privados, por envolverem documentação comercial e dados de clientes.

Trabalhos públicos e de código aberto dos membros ficam em seus perfis pessoais.

## Equipe

| | |
|---|---|
| [@Samuelf27](https://github.com/Samuelf27) | Desenvolvimento full-stack |
| [@paulosardinha](https://github.com/paulosardinha) | Desenvolvimento |

---

<p align="center">
  <sub>DevHub · Brasil</sub>
</p>
