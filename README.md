# ⚡ Power Query ou DAX?

<p align="center">
  <img src="Comparativo-PowerQuery-vs-DAX.png" alt="Comparativo Power Query x DAX" width="900">
</p>

Como resolver o mesmo problema utilizando **Power Query** ou **DAX** no Power BI.

Este projeto apresenta duas abordagens para criar uma classificação por faixas, ajudando a escolher a solução mais adequada para cada cenário.

---

## 📂 Arquivos

- 📄 `PowerQuery_ClassificacaoPorFaixas.m`
- 📄 `DAX_ClassificacaoPorFaixas.dax`
- 🖼️ `Comparativo-PowerQuery-vs-DAX.png`

---

## 🎯 Problema

Classificar registros em categorias, por exemplo:

- Baixo
- Médio
- Alto

---

## 📌 Quando utilizar cada abordagem

| Power Query | DAX |
|--------------|-----|
| Transformação dos dados | Cálculos dinâmicos |
| Regras fixas | Depende do contexto do relatório |
| Executado durante o carregamento | Executado durante a consulta |
| Melhor desempenho para transformações | Maior flexibilidade para análises |

---

## 🚀 Como utilizar

### Power Query

1. Abra o **Editor do Power Query**.
2. Crie uma **Coluna Personalizada**.
3. Cole o código do arquivo `PowerQuery_ClassificacaoPorFaixas.m`.
4. Ajuste o nome da tabela, da coluna e das faixas conforme necessário.

### DAX

1. Acesse **Modelagem → Nova Coluna**.
2. Cole o código do arquivo `DAX_ClassificacaoPorFaixas.dax`.
3. Ajuste o nome da tabela, da coluna e das faixas conforme o seu modelo.

---

## 💡 Objetivo

Disponibilizar um exemplo simples, reutilizável e fácil de adaptar para ajudar profissionais de Power BI a decidir quando utilizar **Power Query** e quando utilizar **DAX** para resolver o mesmo problema.

---

⭐ Se este projeto foi útil, deixe uma estrela no repositório e acompanhe os próximos exemplos da série.
