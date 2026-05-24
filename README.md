# 🪽 Hermes Agent — Curso Completo Avançado

Curso completo em português sobre o **Hermes Agent** da [Nous Research](https://github.com/NousResearch/hermes-agent), no formato INEMA.CLUB.

**Acesse o curso:** https://inematds.github.io/hermesagent/

## Estrutura

6 trilhas progressivas · 12 módulos · 72 tópicos · ~10h de conteúdo

| Trilha | Tema | Nível | Duração |
|--------|------|-------|---------|
| T1 🪽 Fundamentos | O que é, posicionamento, casos de uso | Básico | ~1h30 |
| T2 🏗️ Arquitetura | TUI, gateway, toolsets, MCP, memória, FTS5, Honcho | Intermediário | ~2h |
| T3 ⚙️ Instalação | Linux, macOS, WSL2, Termux, Windows, providers, canais | Básico | ~1h30 |
| T4 🛠️ Manutenção | doctor, update, logs, backup, segurança, monitoramento | Intermediário | ~1h30 |
| T5 🚀 Deployment | 7 backends + AWS Bedrock AgentCore com Firecracker | Avançado | ~2h |
| T6 🧩 Extensibilidade | Skills próprias, MCP servers, Tool Gateway, contribuição | Avançado | ~2h |

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
