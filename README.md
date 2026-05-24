# 🪽 Hermes Agent — Curso Completo Avançado

Curso completo em português sobre o **Hermes Agent** da [Nous Research](https://github.com/NousResearch/hermes-agent), no formato INEMA.CLUB.

**Acesse o curso:** https://inematds.github.io/hermesagent/

## Estrutura

6 trilhas progressivas · **24 módulos** · **144 tópicos** · **~21h** de conteúdo

| Trilha | Tema | Módulos | Duração |
|--------|------|---------|---------|
| T1 🪽 Fundamentos | Definição, posicionamento, casos, glossário, estudo de caso 30 dias | 4 | ~3h |
| T2 🏗️ Arquitetura | TUI, gateway, MCP, memória, FTS5, anatomia de requisição, segurança | 4 | ~4h |
| T3 ⚙️ Instalação | Linux/macOS/WSL2/Termux/Windows, providers, multi-tenancy, top 20 erros | 4 | ~3h |
| T4 🛠️ Manutenção | doctor/update/logs/backup/security + custos (-60%) + upgrade strategy | 4 | ~3h |
| T5 🚀 Deployment | 7 backends, AWS Bedrock AgentCore, observabilidade OTel, CI/CD GitHub Actions | 4 | ~4h |
| T6 🧩 Extensibilidade | Skills + MCP + Tool Gateway + padrões avançados + MCP server próprio | 4 | ~4h |

## Como rodar localmente

```bash
git clone https://github.com/inematds/hermesagent.git
cd hermesagent
python3 -m http.server 8000
# abra http://localhost:8000
```

Site estático puro (HTML + Tailwind via CDN). Sem build step.

## Sobre o material

Material educacional independente. Hermes Agent é projeto open source (MIT) da Nous Research. Referências:

- Repositório: https://github.com/NousResearch/hermes-agent
- Docs oficiais: https://hermes-agent.nousresearch.com/docs/
- AWS Sample: https://github.com/aws-samples/sample-host-hermesagent-on-amazon-bedrock-agentcore
- Discord: https://discord.gg/NousResearch

## Licença

CC BY-SA 4.0 — use, adapte, compartilhe com atribuição.
