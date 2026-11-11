## Matheus Bravo

AI Fullstack Engineer | Taghos Tecnologia

Desenvolvo software profissionalmente desde set/2022 (Taghos). Hoje sou AI Fullstack Engineer na Taghos Tecnologia, nos produtos Estudali LMS e Spalla Stream: desenvolvo como fullstack, com agentes de IA como suporte, e crio funcionalidades que usam LLM em sistemas. De jan/2025 a set/2026 fui Tech Lead do Estudali LMS (referência técnica de uma equipe de 4 devs: revisão de código e desenho das soluções). Hoje meu foco é construir funcionalidades, e ainda acompanho a equipe.

**Stack**

- Backend: Go, Node.js, TypeScript
- Bancos: PostgreSQL, MongoDB, Redis
- Mensageria: RabbitMQ
- Infra: Docker, GitHub Actions, Linux em servidor de produção (máquina alugada em provedor), Loki + Grafana
- Frontend: React (uso secundário)

**Destaques de trabalho**

- **TV Justiça+ (STF)**: único desenvolvedor do backend da plataforma (Go + MongoDB), do desenho da arquitetura ao go-live em menos de 1 mês. Infraestrutura e frontend eram de outras pessoas. Queries de 850 ms para menos de 200 ms com índices e aggregations; a solução virou produto OTT whitelabel adotado por outros clientes da Taghos.
- **Spalla Stream**: trabalho no player e no dashboard. O produto transmite eventos de audiência muito alta: o maior teve 6,9 milhões de espectadores simultâneos.
- **Estudali LMS**: checkout assíncrono com fila no RabbitMQ e reprocessamento automático; taxa de erro de ~15% para menos de 0,5% (estimativa, a partir de chamados de suporte).
- **IA aplicada**: geração de ebook a partir das legendas das videoaulas, com a OpenAI API, em produção (prompt direto, sem base vetorial).

**Projetos de estudo públicos**

- [lunch-rush](https://github.com/matheusgb/lunch-rush): sistema de entregas em Go em 6 tiers, de monólito modular a células com fencing verificado em TLA+. Tudo simulado localmente, com os limites documentados.
- [edge](https://github.com/matheusgb/edge): quatro projetos sobre o caminho de uma requisição, do cache à operação em Kubernetes.
- [cyclists](https://github.com/matheusgb/cyclists): API REST em Go (Fiber, GORM, PostgreSQL) para gestão de eventos de ciclismo: login com JWT, inscrição em eventos, e-mail de redefinição de senha, testes unitários e e2e contra Postgres no CI.
- [forge](https://github.com/matheusgb/forge): laboratório de padrões de backend em Python (idempotência, retry, circuit breaker, RLS).

Contato: matheusgbr98@gmail.com · [LinkedIn](https://www.linkedin.com/in/matheusgb)
