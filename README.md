# SintetizeInvest — Planilha de Investimentos (Excel)

Planilha em Excel para simular aportes mensais, projetar patrimônio e estimar dividendos por cenários, incluindo sugestão de alocação por perfil em categorias de FII.

---

## Índice
- [Descrição](#descrição)
- [Objetivo](#objetivo)
- [Ferramentas](#ferramentas)
- [Estrutura da planilha](#estrutura-da-planilha)
- [Percurso](#percurso)
- [Desafio](#desafio)
- [Profile README](#profile-readme)
- [Instruções (PT/BR)](#instruções-ptbr)
- [Licença](#licença)

---

## Descrição
Este repositório contém uma planilha de planejamento e simulação financeira com foco em:
- projeção de patrimônio por tempo
- estimativa de dividendos (conforme taxa/rendimento informados)
- comparação de cenários
- alocação sugerida por perfil e por tipos de FII

---

## Objetivo
- Visualizar o impacto de **aporte + tempo + taxa**
- Comparar cenários de curto, médio e longo prazo
- Padronizar uma lógica simples de **perfil do investidor x alocação**
- Servir como base para evoluções (gráficos, metas, inflação, etc.)

---

## Ferramentas
- **Microsoft Excel** (recomendado 2019/365)
- Funções financeiras e de busca (ex.: **FV**, **PROCV/VLOOKUP**)
- Tabelas de apoio para percentuais de alocação por perfil

---

## Estrutura da planilha
A planilha está organizada em duas abas principais:

### Aba: `Cenario`
Onde você define os parâmetros e visualiza as simulações, normalmente incluindo:
- aporte mensal
- prazo (anos)
- taxa/rendimento
- projeção de patrimônio
- cenários (ex.: 2, 7, 10, 20, 30 anos)
- estimativa de dividendos (se configurado)

### Aba: `Perfil Investidor e FII's`
Base de referência para a alocação sugerida, normalmente incluindo:
- perfis (Conservador / Moderado / Agressivo)
- categorias de FII
- percentuais por categoria
- cálculo de distribuição por classe (quando aplicado)
