# SaaS Opportunity Insights — Mercado Brasileiro
> Gerado na sessão com Advisory Board (Ray Dalio, Peter Thiel, Charlie Munger, Naval Ravikant)
> Data: 2026-04-19

---

## O Modelo de Referência — "Caso Marcelo"

Marcelo identificou que o mercado de **cookie consent / LGPD** no Brasil só tinha soluções americanas em dólar com preços proibitivos. Construiu uma alternativa local em reais e hoje gera receita recorrente consistente.

**O padrão:** Regulação brasileira obrigatória + só soluções estrangeiras caras + sem alternativa local = oportunidade.

---

## O Filtro de 5 Critérios (Obrigatório para validar qualquer oportunidade)

| # | Critério | Pergunta-chave | Peso |
|---|---|---|---|
| 1 | **Gatilho regulatório** | Existe lei BR (LGPD, BACEN, CVM, ANS, CFM...) que obriga o uso? | ALTO |
| 2 | **Gap de preço** | Solução estrangeira custa 5x+ mais em dólar? | ALTO |
| 3 | **Barreira de localização** | Precisa de português, real, NF-e, suporte local? | MÉDIO |
| 4 | **Tamanho de mercado** | TAM ≥ R$10M/ano no Brasil? | MÉDIO |
| 5 | **Teto de complexidade** | Complexo o suficiente para grandes players ignorarem? | MÉDIO |

> Critérios 1 + 2 são obrigatórios. Os demais somam peso.

---

## Template de Diagnóstico Sistemático (Ray Dalio)

```
DIMENSÃO 1 — OBRIGATORIEDADE
  Existe lei/resolução/circular que obriga o uso?
  Órgão: BACEN / CVM / ANS / ANVISA / Receita / CFM / LGPD / outros
  Penalidade por descumprimento: R$___
  Data limite ou vigência: ___

DIMENSÃO 2 — VÁCUO DE MERCADO
  Soluções existentes: [nome + país + preço em USD]
  Soluções locais decentes: [sim/não]
  Qualidade do atendimento local: [1-5]

DIMENSÃO 3 — TAMANHO DO MERCADO
  Número de empresas obrigadas: ___
  Ticket médio viável: R$___/mês
  MRR potencial: R$___

DIMENSÃO 4 — BARREIRA CONTRA ESTRANGEIROS
  Integração com infra BR necessária: [Pix/NF-e/eSocial/SPED/ICP/outros]
  Conhecimento regulatório específico BR: [alto/médio/baixo]
  Custo de certificação para estrangeiro: [alto/médio/baixo]

DIMENSÃO 5 — VELOCIDADE PARA MVP
  Complexidade técnica: [alta/média/baixa]
  Tempo estimado de MVP: ___ semanas
  Barreira técnica para copiar: [alta/média/baixa]
```

---

## 12 Oportunidades Identificadas

### TIER 1 — Alta Prioridade

#### 1. DPO as a Service — LGPD (Score: 9.2/10) ⭐ RECOMENDADA
- **Obrigação:** Art. 41 LGPD exige Encarregado (DPO) para toda empresa que trata dados
- **Multa:** Até 2% do faturamento ou R$50M por infração
- **Mercado:** 5M+ PMEs brasileiras sem DPO acessível
- **Concorrência:** OneTrust (US, R$30k+/ano), consultorias (R$8-25k/mês)
- **Vácuo:** Nenhum SaaS simples abaixo de R$1.000/mês para PME
- **Barreira para estrangeiro:** Alta — ANPD, portarias brasileiras, jurisprudência local
- **Ticket viável:** R$197-997/mês
- **Tempo para MVP:** 8-12 semanas

#### 2. Telemedicina CFM-Compliant (Score: 8.8/10) ⭐ RECOMENDADA
- **Obrigação:** CFM Resolução 2.314/2022 — prontuário certificado, assinatura ICP-Brasil, dados em servidor BR
- **Mercado:** 550.000 médicos, 30-40% fazendo telemedicina
- **Concorrência:** DrChrono, Kareo (US, USD 200-500/mês) — não integram ICP-Brasil, TISS, CID-10 BR
- **Barreira para estrangeiro:** Máxima — ICP-Brasil intransponível sem operação local
- **Ticket viável:** R$300-600/mês por médico
- **Tempo para MVP (nicho particular):** 20-32 semanas

#### 3. eSocial Simplificado para PME (Score: 8.5/10) ⭐ RECOMENDADA
- **Obrigação:** 100% das empresas com funcionário CLT — 40 eventos distintos
- **Mercado:** 4,2M microempresas com 1-9 funcionários
- **Concorrência:** TOTVS, SAP — caros e complexos demais para PME; 60% usam contador + planilha
- **Barreira para estrangeiro:** Máxima — eSocial, ICP-Brasil, FGTS Digital, CAGED, CLT
- **Ticket viável:** R$150-400/mês
- **Tempo para MVP:** 32-52 semanas

#### 4. Relatórios ESG/CVM (Score: 8.1/10)
- **Obrigação:** CVM Resolução 59/2021 — companhias abertas a partir de 2023
- **Mercado:** 700+ abertas + 2.000 em processo de abertura
- **Concorrência:** Workiva (US, USD 1.500-5.000/mês), IBM Envizi (enterprise)
- **Ticket viável:** R$1.500-6.000/mês

#### 5. ANVISA BPF para Farmácias Magistrais (Score: 7.8/10)
- **Obrigação:** ANVISA RDC 301/2019 — BPF obrigatória para fabricantes
- **Mercado:** 8.000+ farmácias magistrais
- **Concorrência:** MasterControl (US, USD 800+/mês), TrackWise (enterprise)
- **Ticket viável:** R$500-2.000/mês

### TIER 2 — Média Prioridade

#### 6. Gestão de Contratos ICP-Brasil
- Assinaturas com validade jurídica plena no Brasil
- DocuSign não integra ICP-Brasil nativamente
- Ticket: R$100-300/mês | Concorrência local: ClickSign, ZapSign

#### 7. Pix Recorrente + Split para Marketplaces
- Stripe e Adyen não suportam Pix recorrente nativamente
- Requer licença BACEN de IP — barreira regulatória alta
- Modelo: % da transação (0.5-1%)

#### 8. Compliance ANVISA — Farmácia Magistral
- SNGPC obrigatório para medicamentos controlados
- 80.000 farmácias reportando com sistemas antigos
- Ticket: R$100-300/mês

#### 9. Declaração IR para MEI/Autônomo
- 15M MEIs declarando com contador ou programa arcaico da Receita
- Risco: Receita pode lançar solução gratuita
- Ticket: R$50-150/ano

#### 10. Gestão de Benefícios Trabalhistas
- 10.000+ CCTs distintas por setor e município
- 6M microempresas sem solução de gestão de VT, VR, plano de saúde
- Ticket: R$15-40/funcionário/mês

### TIER 3 — Oportunidades Emergentes

#### 11. Cap Table / Equity — Marco Legal das Startups
- Lei 182/2021 — ecossistema de startups BR crescendo
- Carta (US) = USD 100+/mês
- Ticket: R$200-800/mês

#### 12. Gestão de Resíduos — SINIR
- Decreto 10.936/2022 — Política Nacional de Resíduos Sólidos
- Fiscalização aumentando 2024-2025
- Ticket: R$300-1.000/mês

---

## Ranking Final de Recomendação

| Rank | Oportunidade | Score | Por que agora? |
|---|---|---|---|
| 🥇 | DPO as a Service | 9.2/10 | Multas ativas, ANPD fiscalizando, sem líder claro no SMB |
| 🥈 | Telemedicina CFM | 8.8/10 | Regulação nova (2022), 550k médicos, americanos bloqueados |
| 🥉 | eSocial PME | 8.5/10 | Obrigação 100%, 4M+ empresas, ticket previsível |
| 4 | ESG/CVM | 8.1/10 | Janela de 2-3 anos, ticket alto, americanos inacessíveis |
| 5 | ANVISA Magistral | 7.8/10 | Nicho concentrado, dor altíssima, fácil encontrar clientes |

---

## Fontes e Referências Regulatórias

- Lei 13.709/2018 — LGPD (Arts. 41 e 52)
- CFM Resolução 2.314/2022 — Telemedicina
- CVM Resolução 59/2021 — ESG
- ANVISA RDC 301/2019 — BPF Farmacêutica
- Decreto 8.373/2014 e fases 2018-2021 — eSocial
- Lei 182/2021 — Marco Legal das Startups
- Decreto 10.936/2022 — SINIR
- IBGE 2023: 6,2M PMEs ativas, 4,2M com 1-9 funcionários
- CFM: 550.000 médicos registrados no Brasil

---

## Sessão: Advisory Board (Dalio, Thiel, Munger, Naval) — 2026-04-20
> Rodada de novas oportunidades após rejeição das 12 anteriores

### TOP 10 Novas Oportunidades Identificadas

| Rank | Oportunidade | Score | Gatilho | TAM | MVP |
|---|---|---|---|---|---|
| 1 | **SNCR Veterinário — Receituário ICP-Brasil** | 8.7 | Deadline jun/2026 ANVISA/CFMV | 170k vets + 40k clínicas | 8-14 sem |
| 2 | **ANTT 6.077 — Compliance TAC/Embarcador** | 8.6 | Res. 6.077/2026 — multa R$10M | 700k TACs + 130k embarcadores | 12-16 sem |
| 3 | **Licitações PME — Pregão-as-a-Service** | 8.5 | Lei 14.133/21 + PNCP | 1M ME/EPP elegíveis | 16-20 sem |
| 4 | **ANATEL ISPs — Outorga Compliance** | 8.2 | Res. 777/2025 — deadline out/2025 | 20k ISPs | 12-16 sem |
| 5 | **SUSEP Registro Apólices Corretoras** | 8.1 | Circulares 710/711/2024 — vigente | 90k corretoras | 16-20 sem |
| 6 | **ANS RN 623 — Interoperabilidade Operadoras** | 8.0 | RN 623/2024 — vigente jul/2025 | 650 operadoras médias | 16-20 sem |
| 7 | **CRECI/COAF PLD Imobiliária** | 8.0 | Res. COAF 36/2021 — fiscalização ativa | 470k corretores + 40k imobiliárias | 16-20 sem |
| 8 | **PNIB Rastreabilidade Bovina** | 7.9 | MAPA PNIB 2025-2032 — obrig. 2027 | 220M cabeças + 5M produtores | 20-28 sem |
| 9 | **Licenciamento Ambiental PME** | 7.8 | CTF/IBAMA + RAPP anual | 400k empresas no CTF | 16-20 sem |
| 10 | **Habite-se / Regularização Imobiliária** | 7.5 | REURB Lei 13.465/17 | 300k construtoras PME | 20-24 sem |

### Top 3 para Aprofundamento Imediato
1. **SNCR Veterinário** — deadline iminente jun/2026, ICP-Brasil como fosso, mercado pet crescendo 13% a.a.
2. **ANTT 6.077** — resolução recente, multa R$10M, mercado pulverizado, zero SaaS para PME
3. **Licitações PME** — maior TAM, dado público raspável (PNCP), despachante humano cobrando R$5k/mês
