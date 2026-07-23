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

Dois dashboards de Business Intelligence construídos em Power BI, conectados a bancos SQL Server, com modelagem relacional, medidas DAX autorais e indicadores orientados a pergunta de negócio — não só visualização.

Este repositório é parte da minha transição de 12 anos em área jurídica/societário para Dados, Analytics e BI. Cada projeto abaixo documenta o modelo de dados real por trás do dashboard, não apenas o resultado visual.

---

## Projetos

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>💇 Studio Patty Leão — BI</h3>
      <p>Dashboard operacional conectado a um schema de 20 tabelas que espelha um sistema real de gestão de salão (agendamento, caixa, estoque, fornecedores, notas fiscais). 19 medidas DAX autorais, incluindo projeção de faturamento e taxa de cancelamento.</p>
      <p><code>Power BI</code> · <code>DAX</code> · <code>SQL Server</code> · <code>Power Query</code></p>
      <p><a href="./studio-patty-leao-bi/README.md"><strong>Ver projeto →</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <h3>🧾 Dashboard de Vendas, Clientes e Regiões</h3>
      <p>Dashboard analítico sobre uma base relacional de pedidos (tabela ponte para resolver M:N pedido↔item), com 14 perguntas de negócio respondidas via DAX, incluindo ranking de produto por região com RANKX + ALLEXCEPT.</p>
      <p><code>Power BI</code> · <code>DAX</code> · <code>SQL Server</code> · <code>Modelagem Relacional</code></p>
      <p><a href="./dashboard-vendas-aula/README.md"><strong>Ver projeto →</strong></a></p>
    </td>
  </tr>
</table>

---

## O que cada dashboard resolve

| Projeto | Perguntas de negócio | Tabelas no modelo | Medidas DAX |
|---|---|---|---|
| Studio Patty Leão BI | 10 | 20 | 19 |
| Dashboard de Vendas | 14 | 6 | 8 |

---

## Estrutura do repositório

```
Portfolio_Power_BI/
│
├── dashboard-vendas-aula/
│   ├── Dashboard_Vendas_Clientes_Regiao.pbix
│   ├── README.md
│   └── assets/
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

Os dados utilizados são simulados/fictícios, gerados para fins acadêmicos e de portfólio. Nenhum dado real de cliente, empresa ou terceiro foi utilizado.

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
