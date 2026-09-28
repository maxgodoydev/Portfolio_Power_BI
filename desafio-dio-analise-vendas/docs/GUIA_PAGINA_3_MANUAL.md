# Guia: criar a Página 3 manualmente (plano B)

Use se o `.pbix` gerado não abrir. Parta do arquivo original do curso:
`Módulo 2/Desafio de Projeto/relatrio criativo.pbix` (repositório julianazanelatto/power_bi_analyst).
A página 3 já existe nele, oculta e vazia.

## Preparação
1. Abra o arquivo no Power BI Desktop.
2. Clique com o botão direito na aba **Página 3** → desmarque **Ocultar página**.
3. Clique com o botão direito na aba → **Renomear** → `Análise Geográfica`.
4. Opcional: copie da página 2 o fundo, o logo e o título (Ctrl+C na página 2, Ctrl+V na página 3) para manter o padrão.

## Mapa 1: vendas e unidades por país
1. Painel **Visualizações** → ícone **Mapa** (bolhas).
2. Do painel **Dados** (tabela `financials`), arraste:
   - `Country` → **Localização**
   - `Sales` → **Tamanho da bolha**
   - `Units Sold` → **Dicas de ferramenta** (é o que o enunciado quer dizer com "atenção aos campos das dicas")
3. Confirme que os campos numéricos estão como **Soma**.
4. Formatar visual → **Geral → Título** → `Vendas (Sales) e Unidades Vendidas por País`.
5. Posição sugerida: grande, à esquerda (é o visual principal).

## Mapa 2: lucro por país
1. Novo visual **Mapa**.
2. `Country` → **Localização**; `Profit` → **Tamanho da bolha**.
3. Título: `Lucro (Profit) por País`.
4. Posição: canto superior direito.

## Pizza: lucro por segmento
1. Novo visual **Gráfico de pizza**.
2. `Segment` → **Legenda**; `Profit` → **Valores** (Soma).
3. Título: `Lucro (Profit) por Segmento`.
4. Rótulos de dados ligados.
5. Posição: canto inferior direito.
6. Atenção: o Enterprise tem lucro negativo e a pizza não desenha valores negativos (veja o README).

## Fechamento
1. Alinhe os visuais: selecione todos → **Formato → Alinhar** e **Distribuir**.
2. Confira os números com `conferencia_por_pais.csv` e `conferencia_por_segmento.csv`.
3. **Arquivo → Salvar**.
4. **Página Inicial → Publicar** (exige conta do Power BI Service).
5. No PowerPoint: **Inserir → Suplementos → Power BI**, e cole o link do relatório publicado. Sem PowerPoint, basta salvar o `.pbix`.
