<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
  <div class="container">
    <h1>Dashboard Analítico de Vendas - Power BI</h1>
    <p>Bem-vindo ao repositório do <strong>Dashboard Analítico de Vendas</strong>. Este projeto foi desenvolvido utilizando <strong>Power BI</strong> e dados provenientes de quatro arquivos Excel: Clientes, Pedidos, Produtos e Vendas. O objetivo principal foi criar uma análise abrangente de vendas, custos, margens de lucro e KPIs para responder a perguntas-chave do negócio.</p>
    <h2>📊 Funcionalidades do Dashboard</h2>
    <ul>
      <li><strong>Total de valor de venda por modo de envio:</strong> Representado através de um gráfico de cascata.</li>
      <li><strong>Mercados com maior custo médio de envio:</strong> Visualizado com um gráfico Treemap.</li>
      <li><strong>Média de valor de venda e metas:</strong> Indicador KPI para acompanhar o desempenho em relação à meta de 350.</li>
      <li><strong>Lucro médio por categoria:</strong> Cálculo do lucro como <code>valor venda - custo envio</code>.</li>
      <li><strong>Comportamento da margem de lucro ao longo do tempo:</strong> Avaliado como <code>lucro / valor venda</code>.</li>
    </ul>
    <h2>🛠️ Processos Realizados</h2>
    <ul>
      <li>Transformação de dados e limpeza, incluindo remoção de duplicatas.</li>
      <li>Modelagem de dados e verificação de relacionamentos.</li>
      <li>Criação de métricas utilizando <strong>DAX</strong> (Data Analysis Expressions).</li>
    </ul>
    <h2>🧐 Perguntas Respondidas</h2>
    <ol>
      <li><strong>Qual foi o total de valor de venda considerando cada modo de envio dos pedidos?</strong><br> Representado por um gráfico de cascata.</li>
      <li><strong>Quais mercados tiveram o maior custo médio de envio dos produtos vendidos?</strong><br> Exibido em um gráfico Treemap.</li>
      <li><strong>A empresa atingiu a meta de valor de venda em abril de 2014?</strong><br> Avaliado com um indicador KPI.</li>
      <li><strong>Considerando o lucro, qual categoria de produto apresentou maior lucro médio?</strong></li>
      <li><strong>Como foi o comportamento da margem de lucro ao longo do tempo?</strong></li>
    </ol>
    <h2>📂 Estrutura dos Dados</h2>
    <ul>
      <li><strong>Clientes:</strong> Informações sobre os clientes.</li>
      <li><strong>Pedidos:</strong> Detalhes de cada pedido.</li>
      <li><strong>Produtos:</strong> Descrição e categorias de produtos.</li>
      <li><strong>Vendas:</strong> Valores de vendas e custos de envio.</li>
    </ul>
    <h2>📌 Ferramentas Utilizadas</h2>
    <ul>
      <li><strong>Power BI:</strong> Criação de relatórios e dashboards.</li>
      <li><strong>Excel:</strong> Fonte de dados.</li>
      <li><strong>DAX:</strong> Criação de métricas e cálculos.</li>
    </ul>
      <h2>📈 Insights Obtidos</h2>
    <ol>
      <li><strong>Média de Lucro por Categoria:</strong>
        <ul>
          <li>A categoria "Tecnologia" apresentou o maior lucro médio, responsável por 47% do total. Isso indica que investir em produtos tecnológicos pode ser uma estratégia lucrativa.</li>
          <li>Por outro lado, "Material de Escritório" apresentou o menor lucro médio, sugerindo uma análise para reduzir custos ou reavaliar os preços dessa categoria.</li>
        </ul>
      </li>
      <li><strong>Soma de Valor de Venda por Modo de Envio:</strong>
        <ul>
          <li>O modo de envio "Mesmo Dia" contribuiu significativamente para o valor total de vendas, indicando que os clientes valorizam entregas rápidas.</li>
          <li>Modos de envio como "Classe Padrão" e "Segunda Classe" ainda têm peso relevante, mas podem ser áreas para explorar melhorias de custo ou eficiência.</li>
        </ul>
      </li>
      <li><strong>Média de Custo de Envio por Mercado:</strong>
        <ul>
          <li>O mercado APAC apresentou o maior custo médio de envio (29,14), seguido pelos mercados US (28,94) e EU (27,84).</li>
          <li>Mercados como EMEA e Canadá tiveram custos menores, indicando potencial para expandir margens nesses locais.</li>
        </ul>
      </li>
      <li><strong>KPI - Média de Valor de Venda:</strong>
        <ul>
          <li>A média de valor de venda está abaixo da meta de 350, com um resultado de 246,49. Isso mostra a necessidade de estratégias para aumentar o valor médio das vendas.</li>
        </ul>
      </li>
      <li><strong>Comportamento da Margem de Lucro ao Longo do Tempo:</strong>
        <ul>
          <li>A margem de lucro apresenta variações significativas ao longo do tempo. Investigar os períodos de maior estabilidade ou instabilidade ajudam a identificar fatores que afetam diretamente os lucros.</li>
        </ul>
      </li>
    </ol>
    <h2>📷 Visualizações do Dashboard</h2>
    <img src="https://github.com/naralicecosta/lab2-dashboardDeVendasCustoMargemdeLucroeKPI/blob/main/image/imgdash.png" >
    <h2>🚀 Como Utilizar</h2>
    <p>Baixe os arquivos do repositório, abra o arquivo <strong>Power BI</strong> e conecte as fontes de dados.</p>
    <h2>📄 Licença</h2>
    <p>Este projeto é de uso livre. Sinta-se à vontade para utilizar e modificar conforme necessário.</p>
    <footer>
      <p>Desenvolvido por <a href="https://github.com/naralicecosta">Naralice Costa</a>, entusiasta de análise de dados e visualização interativa, com foco em storytelling de dados.</p>
    </footer>
  </div>
</body>
</html>
