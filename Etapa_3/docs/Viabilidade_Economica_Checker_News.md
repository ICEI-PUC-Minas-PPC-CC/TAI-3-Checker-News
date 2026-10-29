# Checker News — Viabilidade econômica e rentabilidade (cenário acadêmico revisado)

**Etapa 3 — 29/10/2026**  
**Aviso:** este é um exercício de planejamento financeiro e **não registra compras, receitas, usuários ou assinaturas reais**. Nenhuma previsão é garantia de lucro. Esta versão corresponde ao cenário MVP acadêmico enxuto e acompanha o arquivo «Plano de Negócios» revisado, fornecido separadamente para atualização da etapa anterior.

## 1. Proposta de receita

O Checker News é uma ferramenta de apoio à checagem de notícias e mensagens, sem prometer identificar com certeza absoluta conteúdos verdadeiros ou falsos. Para simular a sustentação financeira, propõe-se o modelo **freemium**:

| Plano | Proposta hipotética | Preço projetado |
| --- | --- | ---: |
| Gratuito | Uma análise simples por mês, com informações de apoio e indicação das limitações | R$ 0 |
| Premium | Histórico e informações detalhadas e consumo médio estimado de oito consultas por mês | **R$ 12,90/mês** |
| Institucional | Possível oferta para escolas e organizações, sujeita a validação | A definir — receita zero na projeção |

O preço de R$ 12,90 foi **informado pela equipe como a escolha mais recente para a Etapa 3**. O preço anterior registrado no Plano de Negócios era R$ 9,90. O arquivo de revisão da etapa anterior que acompanha esta entrega utiliza R$ 12,90; a atualização deve ser publicada no GitHub. Os R$ 12,90 continuam sendo uma hipótese acadêmica, não um preço praticado nem validado com clientes. As quantidades de consultas e os recursos adicionais do Premium são **propostas para avaliação pela equipe**, não funcionalidades já implementadas.

## 2. Por que os custos foram reduzidos

O plano anterior apresentava um orçamento Lean de R$ 770 mensais e desembolso inicial de R$ 1.800, apropriado como cenário de operação mais estruturada. No exercício de implantação **enxuta** consideramos que a equipe acadêmica desenvolve o protótipo com suas ferramentas e trabalho voluntário, sem contratar infraestrutura paga desde o primeiro dia.

| Item | Valor no cenário novo | Base |
| --- | ---: | --- |
| Domínio `.br` | R$ 40/ano | Preço de referência publicado pelo Registro.br |
| Hospedagem web | R$ 0/mês | Plano gratuito do Cloudflare Pages, sob limites de uso |
| Banco de dados | R$ 0/mês | Plano gratuito Supabase, sob limites de uso |
| Serviço de verificação e APIs | **R$ 0,25 por análise** | **Hipótese** de custo médio; exige avaliação real de fornecedores e qualidade |
| Marketing | R$ 0 no início; até R$ 50/mês no 12º mês | **Hipótese** de ações digitais pontuais |
| Outros serviços | R$ 0 inicialmente; R$ 5/mês nos quatro últimos meses | **Hipótese** de pequenos gastos |
| Investimento fixo inicial | R$ 0 | Não há compra inicial de ativos neste cenário; o domínio e os gastos iniciais aparecem no fluxo mensal |
| Taxa de pagamento | 4,5% da receita + R$ 0,25 por cobrança | **Hipótese ilustrativa**, não tarifa contratada |
| Provisão de tributos | 6% da receita | **Hipótese financeira**, não alíquota tributária definida |

O investimento fixo zero **não significa necessidade zero de caixa**: o déficit acumulado de até R$ 102,27 exigiria capital de giro, caso a simulação representasse uma operação real. As gratuidades não são promessas permanentes: serviços podem cobrar após extrapolar a franquia ou suspender recursos quando as condições não forem atendidas. Em lançamento comercial, há ainda gastos com **formalização, contabilidade, remuneração de pessoal, apoio editorial, licenciamento, atendimento, infraestrutura adicional e eventuais taxas de transação maiores**, os quais **não entram** no caixa acadêmico apresentado.

## 3. Premissas de uso e receitas

A simulação considera crescimento orgânico do serviço, começando em novembro de 2026 e terminando em outubro de 2027. Os quatro primeiros meses não recebem assinatura Premium. Em março de 2027 começa um teste hipotético de monetização com cinco pagantes; em outubro de 2027 o exercício considera 850 usuários gratuitos ativos e 45 assinantes Premium.

Para estimar custo de APIs, a planilha considera uma análise por mês por usuário gratuito e **oito análises mensais por assinante Premium**. A cobrança e a provisão de tributos são simuladas sobre a receita mensal. Não foram contabilizadas publicidade ou parcerias institucionais como receita garantida.

## 4. Fluxo de caixa de 12 meses

| Mês | Pagantes | Entradas projetadas | Saídas projetadas | Saldo mensal | Saldo acumulado |
| --- | ---: | ---: | ---: | ---: | ---: |
| Nov/26 | 0 | R$ 0,00 | R$ 46,25 | (R$ 46,25) | (R$ 46,25) |
| Dez/26 | 0 | R$ 0,00 | R$ 10,00 | (R$ 10,00) | (R$ 56,25) |
| Jan/27 | 0 | R$ 0,00 | R$ 17,50 | (R$ 17,50) | (R$ 73,75) |
| Fev/27 | 0 | R$ 0,00 | R$ 25,00 | (R$ 25,00) | (R$ 98,75) |
| Mar/27 | 5 | R$ 64,50 | R$ 68,02 | (R$ 3,52) | (R$ 102,27) |
| Abr/27 | 8 | R$ 103,20 | R$ 93,84 | R$ 9,36 | (R$ 92,91) |
| Mai/27 | 12 | R$ 154,80 | R$ 128,25 | R$ 26,55 | (R$ 66,36) |
| Jun/27 | 16 | R$ 206,40 | R$ 167,67 | R$ 38,73 | (R$ 27,63) |
| Jul/27 | 22 | R$ 283,80 | R$ 224,30 | R$ 59,50 | R$ 31,87 |
| Ago/27 | 29 | R$ 374,10 | R$ 287,03 | R$ 87,07 | R$ 118,94 |
| Set/27 | 37 | R$ 477,30 | R$ 358,37 | R$ 118,93 | R$ 237,87 |
| Out/27 | 45 | R$ 580,50 | R$ 429,70 | R$ 150,80 | R$ 388,67 |

*Totais projetados (calculados com os valores integrais das fórmulas, antes da apresentação com duas casas decimais):* **R$ 2.244,60** de entradas; **R$ 1.855,93** de saídas; **R$ 388,67** de saldo acumulado. Maior déficit de caixa: **R$ 102,27**. O saldo mensal passa a positivo em abril/2027 (mês 6) e o acumulado em julho/2027 (mês 9).

## 5. Ponto de equilíbrio — limitado a este cenário

Em outubro/2027, com 850 usuários gratuitos, cada um fazendo uma análise por mês, o gasto previsto para consultas grátis é de **R$ 212,50**. Somando marketing de R$ 50 e outros R$ 5, as despesas que independem da quantidade de pagantes nesse mês são **R$ 267,50**.

A contribuição estimada de cada assinante Premium é:

`R$ 12,90 × (1 − 0,045 − 0,06) − R$ 0,25 − (8 × R$ 0,25) = R$ 9,30 (aprox.)`

Portanto, seriam necessários aproximadamente **29 assinantes** para cobrir essas despesas **nas condições específicas do mês 12**. Esse resultado **não serve para um cenário com salários, contador, custos de busca maiores ou mudança no perfil de uso**.

## 6. Teste de sensibilidade

O custo técnico por verificação é uma das variáveis de maior incerteza. Mantendo igual o número projetado de usuários e pagantes, mudar essa premissa de R$ 0,25 para R$ 0,40 por análise **transforma o saldo anual em negativo**. A aba `Sensibilidade` da planilha compara três hipóteses (R$ 0,10, R$ 0,25 e R$ 0,40), sem esconder o risco.

## 7. Como explicar para o professor

> O Checker News foi pensado como uma aplicação freemium. A simulação atual representa uma operação inicial enxuta, desenvolvida por estudantes, utilizando serviços gratuitos de hospedagem e banco de dados enquanto estiver dentro dos limites. O domínio custa cerca de R$ 40 por ano, e adotamos uma estimativa de R$ 0,25 por verificação, que precisa ser confirmada. O Premium, proposto para testes a R$ 12,90 por mês, atenderia quem precisa de mais verificações e histórico. Com crescimento gradual até 45 assinantes no 12º mês, a planilha projeta saldo acumulado de R$ 388,67. Esse número representa somente caixa operacional sob premissas acadêmicas: não é lucro garantido e não inclui remuneração da equipe ou todas as despesas de uma empresa registrada. Nossa conclusão é que a proposta merece validação de demanda e dos custos técnicos antes de qualquer lançamento comercial.

**Argumento central:** a ideia pode gerar receita recorrente, mas a rentabilidade comercial ainda é **hipótese**. A qualidade de análise, a transparência das fontes e a disposição dos usuários de pagar precisariam ser testadas.

## 8. Fontes consultadas e integração com o restante do projeto

- [Plano de Negócios atual do Checker News](https://github.com/ICEI-PUC-Minas-PPC-CC/TAI-3-Checker-News/blob/main/Plano%20de%20Neg%C3%B3cios): Plano de Negócios da etapa anterior; o arquivo preparado nesta entrega atualiza seu cenário-base para o MVP acadêmico enxuto.
- [Registro.br — domínio](https://registro.br/dominio): R$ 40 por ano.
- [Cloudflare Pages — preços](https://developers.cloudflare.com/pages/functions/pricing/): custos iniciais e limitações do plano gratuito.
- [Supabase — preços](https://supabase.com/pricing): plano Free e limites de uso.

**Planilha:** [`Fluxo_de_Caixa_Checker_News.xlsx`](../planilhas/Fluxo_de_Caixa_Checker_News.xlsx) (abas: Premissas, Fluxo de Caixa, Resumo e Sensibilidade). **BSC:** [`Balanced_Scorecard_Checker_News.xlsx`](../planilhas/Balanced_Scorecard_Checker_News.xlsx), com metas financeiras atualizadas para esta projeção.
