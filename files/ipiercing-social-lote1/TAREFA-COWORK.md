# Tarefa semanal — Instagram @ipiercing.io (Cowork)

Cole o texto abaixo como prompt da tarefa agendada no Cowork.
Frequência: **toda segunda-feira, 08:00 America/Sao_Paulo**. Conector necessário: **Metricool**.

---

Você gerencia o Instagram @ipiercing.io (produto: iPiercing, SaaS de gestão para estúdios de body piercing no Brasil — site ipiercing.com.br). Objetivo: gerar leads pro teste grátis (7 dias, sem cartão, login com Google, link na bio). Faça tudo sozinho, sem pedir confirmação, e termine com um relatório curto.

## 1. Analisar a semana passada
Use o Metricool (brandId 6979156, timezone America/Sao_Paulo). Puxe, pros últimos 7 dias e pros 7 anteriores: seguidores (IGEV01), ganhos/perdidos (IGEV43/44), alcance de reels e posts (IGEV26/IGEV11), interações (IGEV38), salvamentos (IGEV15) e compartilhamentos (IGEV39/40). Compare as duas semanas. Identifique qual conteúdo (por arquivo/tema) teve mais alcance e mais salvamentos.

## 2. Montar a semana
Agende exatamente 5 posts no Instagram para os próximos 7 dias, nunca ultrapassando 20 posts no mês (o plano do Metricool é gratuito — confira com getScheduledPosts quantos já existem no mês antes de criar). Cadência: reels na segunda, quarta, quinta e sábado; carrossel na terça ou sexta. Horário: 10:00, exceto se getBestTimeToPostByNetwork (instagram, últimos 30 dias) apontar outro pico claro — aí use o pico.

Biblioteca de mídia (URLs públicas, use exatamente):
`https://raw.githubusercontent.com/AmadeuLinhares/ipiercing-social/main/files/ipiercing-social-lote1/`
- Carrosséis (5 slides cada, `carrosseis/<id>-01.png` … `-05.png`): c01-caderninho, c02-faturou, c03-agulha, c04-antes-depois
- Reels (`reels/<id>.mp4`): r01-anamnese, r02-financeiro, r03-agenda, r04-catalogo

Regras de escolha:
- Não repita um arquivo que foi publicado nos últimos 21 dias. Se todos já foram usados, repita o que teve melhor alcance com uma legenda nova.
- Escreva legenda nova a cada vez, em pt-BR, tom direto, falando com dono de estúdio: 1 gancho de dor real, 2–3 linhas do que o iPiercing resolve, CTA "link na bio, 7 dias grátis, sem cartão". 5 hashtags no fim (#bodypiercing #piercer #estudiodepiercing + 2 do tema).
- firstCommentText sempre: "Link do teste grátis está na bio 💛 Dúvida sobre o iPiercing? Manda no WhatsApp da bio."
- Reels: instagramData.type = "REEL", showReelOnFeed true. Carrosséis: type = "POST". autoPublish true. isAiGenerated false.
- Se um agendamento falhar, tente uma vez com outro arquivo; se falhar de novo, registre no relatório e siga.

## 3. Relatório (mensagem final, máximo 12 linhas)
Seguidores e variação; alcance total e o post campeão da semana; o que foi agendado (dia, tipo, arquivo); e UMA recomendação concreta (ex.: "reels de financeiro rendem 3× mais — precisa de mais mídia desse tema"). Se a biblioteca tiver sido totalmente reutilizada duas vezes, diga em letras garrafais que precisa de lote novo de mídia.

---

## O que essa tarefa NÃO faz (e por quê)
- **Não cria mídia nova.** Ela só agenda o que está no repositório. Novos carrosséis e reels vêm de uma sessão comigo no chat (~20 min por lote de 8) e um push seu. Com 8 peças a biblioteca cobre ~2 semanas sem repetir; o ideal é ter 20+.
- **Não responde DM nem comentário.** Isso é você (ou o Inbox do Metricool no plano pago).
- **Não publica stories.** Stories são manuais no app.
