# Planejamento do Kanban — Checker News, Etapa 3

> **Data-alvo da entrega: 29/10/2026.**  
> Este arquivo é um **roteiro de criação/atualização de cards**. Ele não substitui um quadro real no GitHub Projects nem comprova que tarefas foram concluídas.

## 1. Colunas sugeridas

`Backlog` → `A fazer` → `Em andamento` → `Em revisão` → `Concluído`

Criar cada tarefa como **Issue** no repositório, atribuir uma pessoa, aplicar prioridade e vinculá-la ao **GitHub Project**. Ao passar para “Concluído”, vincular o commit/PR e o arquivo entregue. **Não marcar como concluído sem evidência.**

## 2. Cards a criar

| ID | Card (título de Issue sugerido) | Responsável sugerido | Prioridade | Critério de aceite | Estado inicial sugerido |
| --- | --- | --- | --- | --- | --- |
| CN-31 | [Etapa 3] Preparar Balanced Scorecard | Angelo Henrique Assalim | Alta | Planilha `.xlsx` com quatro perspectivas, três objetivos por perspectiva, KPI, meta, prazo e responsável | Em revisão após upload |
| CN-32 | [Etapa 3] Elaborar matriz SWOT | Angelo Henrique Assalim | Alta | Forças, fraquezas, oportunidades, ameaças e estratégias FO/DO/FA/DA documentadas | Em revisão após upload |
| CN-33 | [Etapa 3] Construir fluxo de caixa de 12 meses | Angelo Henrique Assalim | Alta | Receitas, custos, investimento, saldos e premissas com fórmulas auditáveis | Em revisão após upload |
| CN-34 | [Etapa 3] Defender viabilidade/rentabilidade | Angelo Henrique Assalim | Alta | Modelo freemium, premissas e limites explicados, sem afirmar faturamento real | Em revisão após upload |
| CN-35 | [Etapa 3] Atualizar Kanban e vincular Issues/PRs | Angelo Henrique Assalim | Alta | Projeto GitHub com colunas, cards atribuídos e links de evidência | A fazer até atualizar quadro real |
| CN-36 | [Etapa 3] Auditar documentação de etapas anteriores | Angelo Henrique Assalim | Alta | Checklist com arquivos existentes, ausências e ações corretivas | Em revisão após upload |
| CN-37 | [Etapa 3] Documentar Projeto de Interface.md | Membro responsável por UI | Alta | Telas, navegação e estados documentados; links para implementação | A fazer / confirmar |
| CN-38 | [Etapa 3] Documentar Template.md | Membro responsável por UI | Alta | Tipografia, cores, componentes e padrão visual documentados | A fazer / confirmar |
| CN-39 | [Etapa 3] Documentar Arquitetura do Sistema.md | Membro responsável por backend | Alta | Stack, componentes, dados, API e decisões justificadas | A fazer / confirmar |
| CN-40 | [Etapa 3] Implementar telas reais do MVP | Equipe de frontend | Crítica | Código executável de entrada de notícia, análise e resultado com estados de carregamento/erro | A fazer / confirmar |
| CN-41 | [Etapa 3] Iniciar backend de verificação | Equipe de backend | Crítica | Endpoint básico com validação, respostas consistentes e integração testável | A fazer / confirmar |
| CN-42 | [Etapa 3] Registrar contribuição individual por membro | Todos | Crítica | Cada integrante com commits próprios, descrição da participação e PRs quando aplicável | A fazer / confirmar |
| CN-43 | [Etapa 3] Atualizar índice do README | Documentação / equipe | Alta | Links navegáveis a todos os arquivos e planilhas de entrega | A fazer / confirmar |

**Observação:** responsável e status dos cards de outras pessoas exigem confirmação. Não usar este planejamento como prova de execução de tarefas ainda não observadas.

## 3. Organização de Issues e branches

- **Labels:** `etapa-3`, `documentacao`, `financeiro`, `frontend`, `backend`, `testes`, `prioridade-alta`.
- **Branch documental:** `docs/etapa3-angelo`.
- **Branches técnicas (exemplos):** `feature/tela-verificacao`, `feature/resultado-verificacao`, `feature/api-verificacao`.
- **Modelo de commit:** `docs: adiciona BSC e SWOT da etapa 3`; `docs: adiciona fluxo de caixa e viabilidade`.
- **Pull request:** descrever o que mudou, vincular a Issue (ex.: `Closes #NUMERO` se for de fato concluída) e solicitar revisão.
- **Gitflow simplificado:** `main` estável; `develop` para integração; `feature/*` para desenvolvimento; `docs/*` para documentação, se adotado pela equipe. Não criar branches incompatíveis com o fluxo que a equipe já estiver usando.

## 4. Modelo de descrição para Issue

```md
## Objetivo
Descrever o resultado esperado.

## Entregáveis
- [ ] Arquivo ou funcionalidade no GitHub
- [ ] Evidência (caminho, commit, print ou teste)
- [ ] Revisão pelo grupo

## Critérios de aceite
Listar condição verificável.

## Responsável
@usuario-github

## Prazo
29/10/2026
```

## 5. Checklist de fechamento para hoje

- [ ] Fazer upload dos dois `.xlsx` em `Etapa_3/planilhas/` e dos quatro documentos `.md` em `Etapa_3/docs/`.
- [ ] Criar ou atualizar **de verdade** o quadro GitHub Projects e vincular as Issues.
- [ ] Inserir links da Etapa 3 no `README.md` (manter o Documento de Contexto já existente).
- [ ] Revisar com os demais integrantes os três arquivos de UI/arquitetura.
- [ ] Confirmar commits de cada integrante, especialmente das telas implementadas.
- [ ] Registrar somente funcionalidades demonstráveis; não chamar protótipo de implementação.

**Repositório:** https://github.com/ICEI-PUC-Minas-PPC-CC/TAI-3-Checker-News
