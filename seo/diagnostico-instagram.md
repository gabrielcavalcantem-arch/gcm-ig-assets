# Diagnóstico de Instagram — @gcmbestservicescorp

> Dados **reais** puxados via Windsor.ai (conector Instagram) em 2026-06-11.
> Conta: **GCM Best Services Corp** · Janela analisada: **05/mar → 31/mai 2026** (95 posts).
> Cálculos em `seo/_ig_analysis.py`.

---

## 📸 Snapshot do perfil (hoje)

| Métrica | Valor |
|---|---|
| Seguidores | **616** |
| Seguindo | 9 |
| Posts publicados (total) | **217** |
| Bio | `🏗️ Building with precision and passion` / `📍 Serving Central Florida` / `📞 Call (407) 250-1948` |
| Site na bio | `http://www.gcmbestservicescorp.com` |

---

## 🌎 Audiência — está certa, e isso é a melhor notícia

- **90,6% nos EUA** (558 de 616). Brasil é só ~7% (43) — ruído pequeno, provavelmente conhecidos.
- **Concentração exata na área de atendimento:** Orlando 30 · Kissimmee 16 · Saint Cloud 11 · Poinciana 11 · Loughman 9 · Four Corners 8 · Ocoee 8 · Narcoossee 8 · Buenaventura Lakes 7. Isso é **Central Florida puro** — o público é o cliente real.
- **Demografia ideal para o nicho:** homens 25–54 dominam (M.25-34 = 102, M.35-44 = 134, M.45-54 = 74). Ou seja, **~310 dos 616 são homens 25–54** — exatamente o dono de casa que decide e paga um driveway.

> **Conclusão:** o público não é o problema. A conta atrai gente certa, na cidade certa, na idade certa. O gargalo é **alcance e conversão**, não segmentação.

---

## 📊 Performance dos posts (95 posts em ~3 meses)

| Indicador | Valor |
|---|---|
| Cadência | **~1,1 post/dia** (95 em 87 dias) — volume altíssimo |
| Alcance médio / post | **278** |
| Likes médios / post | 4,6 |
| Comentários médios / post | 0,39 |
| **Saves no trimestre inteiro** | **46** (e **62 dos 95 posts tiveram ZERO saves**) |
| Engajamento médio sobre alcance | 2,31% |

### Desempenho por formato

| Formato | Qtd | Alcance mediano | Likes med. | Views med. | Saves (total) |
|---|---|---|---|---|---|
| **Reels** | 59 | **380** | 5,9 | 470 | 38 |
| Carrossel | 12 | 131 | 3,7 | 240 | 3 |
| Imagem | 24 | **101** | 1,7 | 154 | 5 |

**Os 5 posts de maior alcance são TODOS Reels** (1.372 · 1.345 · 1.096 · 699 · 621).

---

## 🔎 Leitura: muito esforço, pouco retorno

1. **Volume não está virando crescimento.** Mais de 1 post por dia, 217 posts no total — e ainda **616 seguidores** com alcance médio de 278. O problema não é frequência; é que o conteúdo não está sendo recompensado pelo algoritmo nem salvo pelas pessoas.
2. **Imagem isolada está morta** (alcance 101, 1,7 like). Quase um terço do esforço (24 posts) vai para o formato de pior desempenho. **Reels alcançam ~3,8× mais** que imagem.
3. **Saves ~zero é o sinal mais grave.** Driveway/patio é um nicho de *inspiração* — as pessoas salvam para "fazer um dia". 62 de 95 posts com zero saves significa que o conteúdo não é "salvável": faltam **antes/depois fortes**, ângulos de transformação e ganchos úteis (custo, tempo, manutenção).
4. **A bio não vende nem rankeia.** "Building with precision and passion / Serving Central Florida" é genérico de *construção* — não diz **paver driveways, patios, walkways**. Sem palavra-chave, sem link de avaliação do Google, sem botão de orçamento/WhatsApp. O site está como `http://www.` — diferente do NAP canônico `https://gcmbestservicescorp.com`.

---

## ✅ O que mudar (em ordem de impacto)

1. **Trocar a bio agora** para algo com palavra-chave + ação. Sugestão:
   ```
   Paver Driveways · Patios · Walkways 🧱
   Orlando & Central Florida · Free estimates
   📞 (407) 250-1948 👇 Get a quote
   ```
   E padronizar o link para **`https://gcmbestservicescorp.com`** (https, sem `www` divergente) — mesma URL do NAP canônico.
2. **Cortar imagem solta. Priorizar Reels** de **antes→depois** (o formato que já comprovadamente alcança 3,8× mais). Meta realista: 4–5 Reels/semana em vez de 1 post/dia de qualquer coisa.
3. **Projetar para SAVE e SHARE**, não só like: Reels com gancho nos 3 primeiros segundos ("Watch this cracked driveway become…"), legenda com custo/tempo/manutenção, CTA "Save this for your next project".
4. **CTA de conversão fixo:** todo post pede DM/orçamento; link na bio aponta para o site (com o `LocalBusiness` schema já criado em `seo/localbusiness-schema.json`) e para a página de avaliações do Google.
5. **Pedir avaliações** aos clientes via os modelos em `seo/review-requests.md` — reforça o SEO local (Map Pack) e dá prova social para o Instagram.

> O público já está certo. Ganho rápido = **menos volume, mais Reels de antes/depois desenhados para serem salvos**, bio que rankeia, e link/Avaliações apontando para conversão.
