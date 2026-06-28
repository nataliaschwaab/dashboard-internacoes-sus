# 🏥 Análise de Internações Hospitalares SUS (2020-2024)

Dashboard interativo em Power BI que analisa custos, diagnósticos, mortalidade e tendências regionais das internações hospitalares pelo SUS no período de 2020 a 2024.

## 📊 Sobre o projeto

Este projeto explora dados públicos do DATASUS para responder perguntas como:

- Quais regiões e estados apresentam maior volume, custo e mortalidade hospitalar?
- Quais diagnósticos mais impactam o sistema em volume e crescimento?
- Como o perfil dos pacientes (sexo, idade, raça/cor) se relaciona com a mortalidade?
- Existe sazonalidade nas internações ao longo do ano?
- Quais estados são mais eficientes (custo x tempo de internação)?

O objetivo é apoiar gestores de saúde pública e analistas na identificação de padrões, alertas e oportunidades de melhoria na rede hospitalar do SUS.

## 🖼️ Prévia das páginas

### 1. Visão Geral: Custos, Diagnósticos e Tendências Regionais
KPIs gerais (81,47 Mi de internações, custo total de R$ 129,87 Bi, taxa de mortalidade de 4,30), principais diagnósticos e evolução por região ano a ano.

### 2. Desempenho Regional: Custo, Permanência e Mortalidade
Ranking dos estados por custo médio de internação, matriz de eficiência (custo x tempo de internação) e evolução da mortalidade hospitalar por região.

### 3. Perfil do Paciente: Sexo, Idade e Raça/Cor
Distribuição das internações por sexo e raça/cor, e taxa de mortalidade por faixa etária e raça.

### 4. Tendências e Alertas: Monitoramento de Indicadores
Página de insights automáticos com alertas (🔴), pontos de atenção (🟡) e oportunidades (🟢) identificados a partir dos dados — como sazonalidade de internações, crescimento de diagnósticos específicos e correlação entre custo e eficiência por estado.

> 💡 Adicione aqui os prints das 4 páginas (`/imagens/pagina1.png`, etc.) para visualização direta no GitHub.

## 📈 Principais métricas (KPIs)

| Indicador | Valor |
|---|---|
| Total de Internações | 81,47 Mi |
| Taxa de Mortalidade | 4,30% |
| CAGR de Internações (2020-2024) | 4,1% a.a. |
| Média de Dias de Internação | 5,77 |
| Custo Total | R$ 129,87 Bi |

## 🔍 Principais insights

- **Esterilização feminina** e **pneumonia** lideram o crescimento absoluto de diagnósticos entre 2020 e 2024.
- Há um padrão sazonal recorrente de pico de internações entre **junho e agosto** em todos os anos analisados.
- A mortalidade cresce de forma acentuada com a idade: de 0,6% (15-29 anos) para 17,4% (75+ anos).
- O **RJ** tem a maior taxa de mortalidade hospitalar (7,6%), acima de estados com custo médio semelhante (SP, RS), sugerindo um problema ligado à eficiência do atendimento.
- Estados do **Sul** (PR, SC, RS) têm os maiores custos médios por internação, mas não lideram em mortalidade — um padrão de "caro, porém com bom desfecho clínico".

## 🛠️ Tecnologias utilizadas

- **Power BI Desktop**
- **DATASUS** como fonte de dados (competência 2020-2024)
- DAX para cálculo de métricas (CAGR, taxa de mortalidade, custo médio)
- Power Query para tratamento e modelagem dos dados

## 📁 Estrutura do projeto

```
├── dashboard.pbix          # Arquivo principal do Power BI
├── README.md               # Este arquivo
└── imagens/                # Screenshots das páginas (opcional)
```

## 🚀 Como usar

1. Clone este repositório ou baixe o arquivo `.pbix`
2. Abra no **Power BI Desktop**
3. Caso necessário, atualize a conexão com a fonte de dados em *Transformar dados > Configurações de fonte de dados*
4. Use os filtros de **Ano** e **Estado** no painel lateral para explorar os dados

## 👤 Autora

**Natalia Schwaab**

---
*Fonte dos dados: DATASUS · Competência 2020–2024*
