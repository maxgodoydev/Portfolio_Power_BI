<div align="center">

<img
  width="100%"
  src="https://capsule-render.vercel.app/api?type=rect&height=160&text=POWER%20BI%20PORTFOLIO&fontSize=36&fontColor=0F172A&fontAlignY=50&color=0:C4F135,100:8FD400&desc=An%C3%A1lise%20de%20Dados%20%C2%B7%20Modelagem%20%C2%B7%20DAX%20%C2%B7%20Dashboards&descAlignY=75&descSize=15&descColor=0F172A"
/>

<br><br>

<img src="https://img.shields.io/badge/POWER%20BI-0F172A?style=flat-square&logo=powerbi&logoColor=F2C811" />
<img src="https://img.shields.io/badge/DAX-0F172A?style=flat-square&labelColor=0F172A&color=C4F135" />
<img src="https://img.shields.io/badge/MODELAGEM%20RELACIONAL-0F172A?style=flat-square&labelColor=0F172A&color=C4F135" />
<img src="https://img.shields.io/badge/SQL%20SERVER-0F172A?style=flat-square&logo=microsoftsqlserver&logoColor=CC2927" />
<img src="https://img.shields.io/badge/STATUS-EM%20EVOLU%C3%87%C3%83O-0F172A?style=flat-square&labelColor=0F172A&color=16A34A" />

</div>

---

## Sobre este portfólio

Três projetos em Power BI. Dois são dashboards de Business Intelligence conectados a bancos SQL Server, com modelagem relacional, medidas DAX autorais e indicadores orientados a pergunta de negócio. O terceiro é um desafio de bootcamp focado em criação de visuais.

Este repositório é parte da minha transição de 12 anos em área jurídica/societário para Dados, Analytics e BI. Cada projeto abaixo documenta o que foi construído, não apenas o resultado visual.

---

## Projetos

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>💇 Studio Patty Leão — BI</h3>
      <p>Dashboard operacional conectado a um schema de 20 tabelas que espelha um sistema real de gestão de salão (agendamento, caixa, estoque, fornecedores, notas fiscais). 19 medidas DAX autorais, incluindo projeção de faturamento e taxa de cancelamento.</p>
      <p><code>Power BI</code> · <code>DAX</code> · <code>SQL Server</code> · <code>Power Query</code></p>
      <p><a href="./studio-patty-leao-bi/README.md"><strong>Ver projeto →</strong></a></p>
    </td>
    <td width="33%" valign="top">
      <h3>🧾 Dashboard de Vendas, Clientes e Regiões</h3>
      <p>Dashboard analítico sobre uma base relacional de pedidos (tabela ponte para resolver M:N pedido↔item), com 14 perguntas de negócio respondidas via DAX, incluindo ranking de produto por região com RANKX + ALLEXCEPT.</p>
      <p><code>Power BI</code> · <code>DAX</code> · <code>SQL Server</code> · <code>Modelagem Relacional</code></p>
      <p><a href="./dashboard-vendas-clientes-regiao/README.md"><strong>Ver projeto →</strong></a></p>
    </td>
    <td width="33%" valign="top">
      <h3>🎓 Desafio DIO — Análise de Vendas</h3>
      <p>Desafio do bootcamp de Power BI da DIO: duas páginas replicadas do curso a partir da base de exemplo e uma terceira criada por mim, com mapas de vendas, unidades vendidas e lucro por país e gráfico de pizza de lucro por segmento.</p>
      <p><code>Power BI</code> · <code>Visualizações</code> · <code>Mapas</code></p>
      <p><a href="./desafio-dio-analise-vendas/README.md"><strong>Ver projeto →</strong></a></p>
    </td>
  </tr>
</table>

---

## O que cada dashboard resolve

| Projeto | Perguntas de negócio | Tabelas no modelo | Medidas DAX |
|---|---|---|---|
| Studio Patty Leão BI | 10 | 20 | 19 |
| Dashboard de Vendas | 14 | 6 | 8 |

> O Desafio DIO não entra na tabela: o foco dele é criação de visuais, não modelagem nem DAX.

---

## Estrutura do repositório

```
Portfolio_Power_BI/
│
├── dashboard-vendas-clientes-regiao/
│   ├── Dashboard_Vendas_Clientes_Regiao.pbix
│   ├── README.md
│   └── assets/
│
├── desafio-dio-analise-vendas/
│
├── studio-patty-leao-bi/
│   ├── Studio_Patty_Leao_BI.pbix
│   ├── README.md
│   └── assets/
│
└── README.md
```

---

## Observação sobre os dados

Os dados dos dois dashboards conectados ao SQL Server são simulados/fictícios, gerados para fins acadêmicos e de portfólio. O Desafio DIO usa a base de exemplo fornecida pelo curso. Nenhum dado real de cliente, empresa ou terceiro foi utilizado.

---

## Autor

<div align="center">

### Max Godoy

Estudante de **Desenvolvimento de Software Multiplataforma — FATEC Zona Sul**, em transição de 12 anos em área jurídica/societário para **Dados, Analytics, BI e Automação de Processos**.

<a href="https://www.linkedin.com/in/max-godoy/">
  <img src="https://img.shields.io/badge/LinkedIn-0F172A?style=flat-square&logo=linkedin&logoColor=C4F135" />
</a>
<a href="mailto:maxgodoy.dev@gmail.com">
  <img src="https://img.shields.io/badge/E--mail-0F172A?style=flat-square&logo=gmail&logoColor=C4F135" />
</a>
<a href="https://github.com/maxgodoydev">
  <img src="https://img.shields.io/badge/GitHub-0F172A?style=flat-square&logo=github&logoColor=C4F135" />
</a>

</div>
