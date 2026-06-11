# 💰 Smart Investment Portfolio

## 📌 Sobre o Projeto

O Smart Investment Portfolio é uma aplicação desenvolvida em Rust para simular uma carteira de investimentos inteligente, permitindo acompanhar a distribuição dos ativos, patrimônio total, score de risco e recomendações automáticas de diversificação.

O projeto foi desenvolvido com foco em aplicar conceitos de programação em Rust, análise financeira e visualização de dados, integrando uma camada de processamento financeiro com um dashboard para acompanhamento dos investimentos.

---

## 🎯 Objetivo

Desenvolver uma solução capaz de:

- Gerenciar ativos de uma carteira de investimentos;
- Calcular patrimônio total;
- Avaliar a distribuição dos ativos;
- Identificar riscos de concentração;
- Gerar recomendações automáticas;
- Exibir informações em um dashboard interativo.

---

## 🚀 Funcionalidades

### Gestão de Ativos

- Cadastro de ativos
- Classificação por categoria

### Indicadores Financeiros

- Patrimônio total
- Distribuição da carteira

### Inteligência da Carteira

- Identificação de concentração excessiva

### Dashboard

- Gráfico de alocação dos ativos

---

## 🛠 Tecnologias Utilizadas

- Rust
- HTML5
- CSS3
- JavaScript
- Chart.js
- JSON

---

## 🏗 Arquitetura da Solução

```text
Rust
 ↓
portfolio.json
 ↓
HTML + CSS + JavaScript
 ↓
Dashboard Interativo
```

### Fluxo

1. Rust processa os dados da carteira.
2. Os resultados são exportados para um arquivo JSON.
3. O dashboard consome os dados.
4. Os gráficos são renderizados utilizando Chart.js.

---

## 📊 Exemplo de Saída

### KPIs

- Patrimônio Total
- Quantidade de Ativos

### Visualizações

- Alocação da Carteira

---

## 📂 Estrutura do Projeto

```text
smart-investment-portfolio/
│
├── Codigo
│
├── post
|
|──Dashboard
│
└── README.md
```

---

## 💡 Conceitos Aplicados

### Rust

- Structs
- Ownership
- Borrowing
- Vetores (Vec)
- Manipulação de Arquivos
- Serialização de Dados

### Mercado Financeiro

- Diversificação
- Gestão de Risco
- Alocação de Ativos
- Patrimônio Líquido
- Rebalanceamento de Carteira

---

## 🔄 Evoluções Futuras

A versão atual do projeto implementa a lógica de processamento da carteira de investimentos em Rust e a visualização dos dados através de um gráfico de alocação utilizando HTML, JavaScript e Chart.js.

Embora o sistema já permita analisar a distribuição dos ativos da carteira, algumas melhorias foram identificadas para versões futuras:

### Dashboard Completo

Transformar a visualização atual em um dashboard financeiro completo, contendo:

- Hero Section com resumo da carteira;
- KPIs financeiros;
- Patrimônio total;
- Rentabilidade acumulada;
- Score de risco;
- Quantidade de ativos;
- Melhor ativo da carteira.

### Novas Visualizações

Implementar gráficos adicionais para ampliar a análise:

- Evolução patrimonial ao longo do tempo;
- Comparação entre classes de ativos;
- Distribuição por categoria;
- Rentabilidade por ativo;
- Histórico de aportes.

### Integração Dinâmica

Atualmente os dados são gerados localmente. Em versões futuras, pretende-se:

- Consumir dados de APIs financeiras;
- Atualizar preços em tempo real;
- Integrar provedores de mercado financeiro;
- Automatizar rebalanceamentos.

### Inteligência da Carteira

Adicionar mecanismos de recomendação mais avançados:

- Perfil de investidor;
- Simulação de cenários;
- Sugestões de diversificação;
- Alertas de concentração excessiva;
- Otimização automática de alocação.

### Melhorias Técnicas

- Utilização de Serde para serialização JSON;
- Arquitetura modular em Rust;
- Interface responsiva;
- Deploy em ambiente cloud;
- Dashboard web em tempo real.

---

### Status Atual

✅ Processamento da carteira em Rust

✅ Geração de dados financeiros

✅ Exportação de informações para JSON

✅ Dashboard HTML

✅ Visualização da composição da carteira

⚠ Dashboard ainda em evolução para uma experiência analítica completa

---
###  Observação:
Este projeto representa um MVP (Minimum Viable Product) de uma plataforma de investimentos inteligente. O foco principal foi demonstrar a integração entre Rust, processamento financeiro e visualização de dados, servindo como base para futuras expansões e funcionalidades mais avançadas.

---
## 🎓 Projeto Desenvolvido

Projeto desenvolvido como parte dos desafios práticos da DIO (Digital Innovation One), com foco na aplicação de Rust em cenários financeiros e análise de investimentos.

---

## 👩‍💻 Autora

**Camila Silva dos Santos**

Graduada em Ciências Econômicas e entusiasta das áreas de Dados, Business Intelligence, Engenharia de Dados e Tecnologia.

---

⭐ Se gostou do projeto, deixe uma estrela no repositório.
