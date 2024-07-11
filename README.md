2ª Aula da Hashtag Treinamentos ministrada com excelência por João Paulo Rodrigues de Lira
O código fornecido realiza a análise de uma base de dados de cancelamentos de clientes.

Passo 1:  Importar a Base de Dados.
          Importa a biblioteca pandas.  
          Lê a base de dados "cancelamentos_sample.csv" e armazena em uma variável tabela.
          
Passo 2:  Visualiza a Base de Dados.
          Remove a coluna "CustomerID" por ser considerada desnecessária.
          Exibe a tabela sem a coluna removida para visualização.
          
Passo 3:  Corrigi Problemas na Base de Dados.
          Exibe informações sobre a tabela, como tipos de dados e valores nulos.
          Remove as linhas com valores nulos.
          Exibe novamente as informações da tabela para confirmar a remoção dos valores nulos.
          
Passo 4:  Análise Inicial dos Cancelamentos.
          Conta quantas pessoas cancelaram e quantas não cancelaram e exibe esses valores.
          Calcula e exibe a proporção de cancelamentos em percentual.
          
Passo 5:  Análise das Causas dos Cancelamentos.
          Utiliza a biblioteca plotly.express para criar gráficos que mostram como diferentes colunas da base de dados impactam o cancelamento.
          Cria e exibe histogramas para cada coluna da tabela, coloridos pelo status de cancelamento.
          
Passo 6:  Ações Baseadas na Análise Identifica que todos os clientes com contrato mensal cancelam e sugere oferecer descontos nos planos anuais e trimestrais.
          Identifica que clientes que ligam mais de 4 vezes para o call center tendem a cancelar e sugere criar um processo para resolver problemas em até 3 ligações.
          Identifica que clientes com mais de 20 dias de atraso tendem a cancelar e sugere uma política para resolver atrasos em até 10 dias.
          
Passo 7:  Filtragem da Tabela com Base nas Ações.
          Remove clientes com contrato mensal.
          Remove clientes que ligaram mais de 4 vezes para o call center.
          Remove clientes que atrasaram mais de 20 dias.
          
Passo 8:  Verificação Final dos Cancelamentos.
          Conta e exibe quantas pessoas cancelaram e quantas não cancelaram na tabela filtrada.
          Calcula e exibe a proporção de cancelamentos em percentual na tabela filtrada.
          Instalação de Dependências.
          
O código inclui comandos para instalar bibliotecas necessárias (pandas, numpy, openpyxl, nbformat, ipykernel, plotly).
O objetivo do código é analisar e reduzir o número de cancelamentos identificando padrões e propondo ações específicas para mitigar os problemas encontrados.
