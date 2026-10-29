# Auditoria da documentação e da entrega — Checker News

> Verificação do **repositório público na branch `main` em 29/10/2026**.  
> Esta é uma fotografia do estado observado; arquivos podem ter sido adicionados posteriormente ou estar em branches não examinadas.

## 1. Arquivos observados na raiz de `main`

| Arquivo | Situação constatada | Observação |
| --- | --- | --- |
| `README.md` | Presente | Documento de Contexto, público-alvo, objetivos, missão/visão/valores; menciona Lean Canvas, mas seu detalhamento deve ser conferido |
| `Especificação de Projeto` | Presente | Contém RF01–RF06 e RNF01–RNF05, fluxo principal de uso |
| `Plano de Negócios` | Presente | Modelo freemium, custos, preço Premium, cenários Lean e Ideal e indicadores |

**Atenção:** os dois últimos arquivos são publicados no repositório **sem extensão `.md`**. É recomendável organizar/renomear para `.md` somente com alinhamento da equipe, atualizando links para evitar quebrá-los.

## 2. Checklist completo da Etapa 3

| Item do professor | Situação na `main` consultada | Quem deverá resolver |
| --- | --- | --- |
| `Projeto de Interface.md` | **Não localizado** | Equipe de UI |
| `Template.md` | **Não localizado** | Equipe de UI |
| `Arquitetura do Sistema.md` | **Não localizado** | Equipe de arquitetura/backend |
| Balanced Scorecard (mínimo 3 objetivos por perspectiva) | **Arquivo preparado para upload** | Responsável por negócio |
| Análise SWOT | **Documento preparado para upload** | Responsável por negócio |
| Planilha de fluxo de caixa | **Arquivo preparado para upload** | Responsável financeiro |
| Contribuições individuais e telas implementadas | **Não evidenciadas na raiz de `main`** | Todos / desenvolvimento |
| Planejamento de stack e backend | **Requer documentação e evidência da equipe** | Arquitetura/backend |
| Commits individuais | Conferir por autor/branch no GitHub | Todos |
| Kanban GitHub Projects | Não foi possível confirmar o quadro como organizado; **roteiro preparado, não executado** | Equipe / gestão |
| Documentação anterior | Contexto, especificação e plano de negócios presentes; revisar completude | Documentação |

Os arquivos preparados nesta entrega **não foram enviados ao GitHub automaticamente**; o status muda após upload e commits reais.

## 3. Pontos de revisão das etapas anteriores

1. **Documento de Contexto** — revisar se o **Lean Canvas completo** (blocos/itens) está realmente presente; o texto atual explica o propósito do Lean Canvas, mas não detalha explicitamente seus blocos.
2. **Especificação** — verificar critérios de aceite, rastreabilidade entre requisitos e telas, e detalhamento da verificação (serviço, fontes, retornos e falhas).
3. **Plano de Negócios** — **arquivo de atualização preparado para publicação**: o arquivo completo `Plano de Negócios` foi revisado neste pacote para **R$ 12,90** e cenário MVP enxuto. A alteração no GitHub permanece pendente até um commit efetivo. Os valores da documentação da Etapa 3 devem ser comparados com a versão publicada após a integração.
4. **Implementação** — documentar repositório de código, comandos de execução, telas reais e backend iniciado. Pelo menos um fluxo simples demonstrável é mais importante que apresentar apenas imagens de protótipo.
5. **Rastreabilidade** — ligar cards do Kanban às Issues, PRs, commits e arquivos de entrega. A autoria do Git deve ser individual e verificável.

## 4. Seção sugerida para incluir no README existente

```md
## Etapa 3 — Planejamento estratégico e financeiro
- [Índice da Etapa 3](Etapa_3/README.md)
- [Balanced Scorecard](Etapa_3/planilhas/Balanced_Scorecard_Checker_News.xlsx)
- [Análise SWOT](Etapa_3/docs/Analise_SWOT_Checker_News.md)
- [Fluxo de Caixa](Etapa_3/planilhas/Fluxo_de_Caixa_Checker_News.xlsx)
- [Viabilidade econômica e rentabilidade](Etapa_3/docs/Viabilidade_Economica_Checker_News.md)
- [Planejamento do Kanban](Etapa_3/docs/Kanban_Etapa_3.md)
- [Auditoria da documentação](Etapa_3/docs/Auditoria_Documentacao.md)
```

Completar também com os links para `Projeto de Interface.md`, `Template.md`, `Arquitetura do Sistema.md` e as pastas do código assim que os respectivos arquivos forem adicionados.

**Fontes:** [Raiz do repositório](https://github.com/ICEI-PUC-Minas-PPC-CC/TAI-3-Checker-News) · [Especificação de Projeto](https://github.com/ICEI-PUC-Minas-PPC-CC/TAI-3-Checker-News/blob/main/Especifica%C3%A7%C3%A3o%20de%20Projeto) · [Plano de Negócios](https://github.com/ICEI-PUC-Minas-PPC-CC/TAI-3-Checker-News/blob/main/Plano%20de%20Neg%C3%B3cios).
