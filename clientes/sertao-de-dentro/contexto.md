<!-- fatos e combinados do cliente. Material bruto (transcrição, PDF, email) é destilado aqui, com data e caminho da fonte. -->
# Contexto · Sertão de Dentro

## O que é
Pizza, churrasco e burguer. Altos-PI.

- Instagram: https://www.instagram.com/sertaodedentroaltos/
- Site: https://sertaodedentro.com.br/
- Google Meu Negócio: https://g.page/r/CZaaaefiAyXsEAE/review

## Marca
Logo em `marca/logo.jpg`.

## Escopo com a Metrik
Gestão de tráfego pago (Meta Ads). Escopo completo ainda não detalhado nesta pasta.

## Observação sobre dados (2026-09-17)
O cliente tem cardápio web (loja/pedido online) — por isso o tráfego é rastreado por pixel de
compra (`actions:offsite_conversion.fb_pixel_purchase`), diferente da maioria dos outros
clientes (que rastreiam conversa iniciada no WhatsApp). No relatório, a métrica principal aqui é
**vendas** (via pixel), não conversas.

Esse cliente também é o único com **faturamento e ticket médio reais**, pedidos pelo usuário em
2026-09-18. Não existe campo direto de faturamento no Meta Ads — calcular assim:
- Pedir o campo `website_purchase_roas` (ROAS) junto com `amount_spent` e `results` de cada
  campanha (nível `campaign`, mesma consulta de sempre).
- Faturamento de cada campanha = `amount_spent × website_purchase_roas` (somar todas as
  campanhas que tiverem ROAS não-nulo, mesmo as que não têm "vendas" como objetivo principal —
  pode haver venda atribuída a campanha de tráfego/alcance também).
- Faturamento total = soma do faturamento de todas as campanhas.
- Ticket médio = faturamento total ÷ total de vendas (soma do `results` das campanhas com
  indicador `actions:offsite_conversion.fb_pixel_purchase`).
- Exemplo real (semana 08/09-14/09): 17 vendas, R$ 575,59 investidos, R$ 1.439,58 de faturamento
  (via ROAS), ticket médio R$ 84,68.

## Contas de anúncio
- **Meta Ads:** `CA1 Sertao de Dentro [ALTOS-PI]` — id `601850290415990`
- **Google Ads:** não conectado no Windsor.ai ainda (2026-09-17)

## Vendas e faturamento
Ainda não conectado a nenhuma fonte automática (2026-09-17). N/A nos relatórios até existir.
