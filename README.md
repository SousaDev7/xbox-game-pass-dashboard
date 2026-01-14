# 🎮 Xbox Game Pass Sales Dashboard (Excel)

Dashboard desenvolvido em **Microsoft Excel** para análise de vendas e assinaturas do **Xbox Game Pass**, incluindo **EA Play** e **Minecraft Season Pass**.

O projeto demonstra organização de dados, criação de métricas e visualização clara de indicadores de negócio.

---

## 📌 Objetivo do Projeto

Transformar dados brutos de vendas em **informações visuais claras e acionáveis**, facilitando a análise de faturamento, desempenho de produtos e status das assinaturas ao longo do período analisado.

---

## 📊 Indicadores Analisados

- 💰 Faturamento total por tipo de assinatura  
- 📦 Comparativo entre produtos (EA Play x Minecraft Season Pass)  
- ✅ Assinaturas ativas e ❌ inativas  
- 📅 Visão consolidada do período anual  

---

## 🗂️ Organização do Projeto

O projeto foi estruturado seguindo boas práticas de organização e separação de responsabilidades:

```text
xbox-game-pass-dashboard/
├── assets/
│   └── assets.xlsx              # Elementos visuais e apoio
│
├── dashboard/
│   └── xbox_game_pass_dashboard.xlsx
│                                # Dashboard final
│
├── data/
│   ├── bases/
│   │   └── vendas_base.xlsx     # Dados brutos
│   └── processed/
│       └── vendas_calculadas.xlsx
│                                # Dados tratados e cálculos
│
├── .gitignore
└── README.md
