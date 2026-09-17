<!-- quem alimenta: o /setup semeia na entrevista; o /atualizar acrescenta ferramenta nova, acesso novo ou "não alcanço"; a /faxina confere e pergunta. Lido antes de dizer "não consigo" e ao criar skill. -->
# Ferramentas

> O que o negócio usa e como o agente alcança cada coisa. **"não ligada" é resposta válida:** é assim
> que o agente sabe que aquilo existe e dá pra ligar, em vez de achar que é impossível.
> Chave nunca fica aqui. Chave mora no `.env` (fora do git) ou no gerenciador de senha; aqui vai só o
> nome da variável. O cardápio do que dá pra ligar está em `sistema/templates/ferramentas/catalogo.md`.

| ferramenta | pra quê | como o agente alcança | estado | última checagem |
|---|---|---|---|---|
| Gmail | email | MCP | ligada | 2026-09-14 |
| Google Drive | arquivos, briefings, contratos | MCP | ligada | 2026-09-14 |
| Meta Ads | gestão de campanhas Facebook/Instagram | MCP | ligada | 2026-09-14 |
| Windsor.ai | dados de Google Ads, GA4, TikTok Ads e outros conectores de mídia/analytics | MCP | ligada | 2026-09-14 |
| ClickUp | tarefa e prazo | sem conector pronto no catálogo | não ligada | 2026-09-14 |
| WhatsApp Business / Z-API | mensagem com cliente | API (precisa conta + token no `.env`); montar junto com a skill que for usar | não ligada | 2026-09-14 |
| Google Meu Negócio | presença local dos clientes | não avaliado ainda | não ligada | 2026-09-14 |
| CRM | ficha do cliente | ferramenta não especificada | não ligada | 2026-09-14 |
| Meta Pixel / GTM | tracking e conversões | não avaliado ainda | não ligada | 2026-09-14 |

## Os sete assuntos que todo negócio tem

- **Mensagem com cliente:** WhatsApp Business / Z-API — não ligada (pendência: montar com token no `.env`)
- **Tarefa e prazo:** ClickUp — não ligada (sem conector pronto no catálogo)
- **Email:** Gmail — ligada (MCP)
- **Agenda:** nada configurado ainda
- **Dinheiro entrando e saindo:** nada configurado ainda (Edilson cuida da parte financeira)
- **Ficha do cliente:** CRM (nome não especificado) — não ligada
- **Reunião:** nada configurado ainda
