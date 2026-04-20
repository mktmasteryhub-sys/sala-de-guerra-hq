# Sala de Guerra HQ — Instruções Operacionais

## Carregamento Automático de Contexto (OBRIGATÓRIO)

Ao iniciar QUALQUER sessão neste projeto, leia imediatamente os 3 arquivos de knowledge antes de responder qualquer coisa:

1. `knowledge/saas-opportunity-insights.md`
2. `knowledge/mental-models.md`
3. `knowledge/agent-learnings.md`

Após ler, faça um briefing de 3 linhas ao usuário:
> "📋 Contexto carregado: [resumo do que está nos arquivos — oportunidades mapeadas, squads ativos, última sessão]"

Isso garante continuidade entre sessões sem o usuário precisar reexplicar o contexto.

---

## Regra de Memória Estratégica (OBRIGATÓRIA)

Após QUALQUER sessão com squads ou agentes que gere insights estratégicos, você DEVE atualizar os arquivos de knowledge em `knowledge/` antes de encerrar.

### Mapeamento de conteúdo → arquivo

| Tipo de conteúdo gerado | Arquivo de destino |
|---|---|
| Oportunidades de mercado, análise de nichos, gaps de SaaS, análise regulatória | `knowledge/saas-opportunity-insights.md` |
| Modelos mentais, frameworks estratégicos, princípios dos conselheiros | `knowledge/mental-models.md` |
| Ofertas, preços, estratégias de go-to-market, outputs de agentes especializados | `knowledge/agent-learnings.md` |

### Quando salvar

Salve ao final de qualquer sessão que envolva:
- Advisory Board (Ray Dalio, Thiel, Munger, Naval, etc.)
- Hormozi Squad (ofertas, preços, modelos)
- Copy Squad (copy, messaging)
- Traffic Masters (aquisição, mídia)
- Brand Squad (posicionamento, naming)
- Data Squad (métricas, growth)
- C-Level Squad (decisões executivas)
- Qualquer outro squad dos xquads-squads

### Como salvar

Não substitua o arquivo inteiro. **Acrescente** o novo conteúdo ao final da seção relevante, com cabeçalho de data:

```
---
## Sessão: [Nome do Squad] — [data]
[conteúdo novo]
```

### Se surgir um tema novo

Se o insight não se encaixa nos 3 arquivos existentes, crie um novo arquivo em `knowledge/` com nome descritivo (ex: `knowledge/copy-frameworks.md`).

---

## Relatório Automático de Sessão (OBRIGATÓRIO)

Ao encerrar qualquer sessão com squad ou board, verifique os gatilhos abaixo.
Se **qualquer um** for verdadeiro → gere o relatório antes de encerrar.

### Gatilhos (qualquer um ativa o relatório)
- Houve decisão estratégica tomada
- Houve definição de próximo passo ou ação
- Houve output utilizável gerado (copy, plano, código, análise, oferta, etc.)

### Formato do Relatório

```markdown
# Relatório de Sessão — [Nome do Squad/Board]
**Data:** [data]
**Participantes:** [agentes/advisors convocados]
**Tema da Sessão:** [assunto principal]

## Decisões Tomadas
- [decisão 1]

## Insights Estratégicos
- [insight 1]

## Próximos Passos
- [ ] [ação 1] — responsável: [quem]

## Outputs Gerados
- [tipo]: [descrição breve]

## Dissidências / Alertas
- [se algum advisor discordou ou levantou risco — ou "Nenhuma"]
```

### Onde Salvar (SEMPRE os dois)

1. **`knowledge/`** — seguir o mapeamento existente (acrescentar ao final do arquivo correto com cabeçalho de data)
2. **`reports/[squad-name]/[YYYY-MM-DD]-[tema-slug].md`** — criar arquivo novo, nunca sobrescrever

---

## Estrutura do Projeto

```
Sala de Guerra HQ/
├── knowledge/          ← memória estratégica (SEMPRE atualizar após sessões)
│   ├── saas-opportunity-insights.md
│   ├── mental-models.md
│   └── agent-learnings.md
├── aios-core/          ← framework de desenvolvimento AIOS (Synkra)
└── xquads-squads/      ← 12 squads de agentes especializados
```

## Idioma

Sempre responda em português.
