# 🚚 Análise Exploratória de Dados de Logística - Loggi

# Descrição do Projeto

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) dos dados logísticos da empresa Loggi. A análise visa entender melhor as operações logísticas, otimizar a distribuição de recursos, melhorar a eficiência das rotas de entrega e identificar áreas que possam ser aprimoradas para aumentar a eficiência operacional e a satisfação do cliente.

# Estrutura do Projeto

# 1. Contexto

• Objetivo: Organizar e analisar dados brutos de entregas, fornecidos em formato JSON, para extrair insights valiosos que     
  ajudem na tomada de decisões estratégicas.

• Dados: Os dados incluem informações sobre as cidades, quantidade de entregas, frequência de entrega, capacidade dos 
  veículos, e outras características importantes.

  # 2. Pacotes e Bibliotecas

  • Foram utilizados diversos pacotes e bibliotecas do Python para a manipulação e visualização dos dados, incluindo pandas,   
    geopy, geopandas, matplotlib, e seaborn.

  # 3. Exploração de Dados

  # 3.1 Coleta de Dados
  
  • 3.1.1: Os dados foram obtidos e carregados em um formato JSON.
  • 3.1.2: Os dados foram carregados em um dicionário Python para facilitar a manipulação subsequente.

  # 3.2 Wrangling dos Dados

  • 3.2.1: A coluna origin foi normalizada, transformando dados aninhados em colunas planas.
  • 3.2.2: A coluna deliveries foi explodida para separar cada entrega em uma linha, facilitando a análise detalhada.

  # 3.3 Estrutura dos Dados

  • Foi realizada uma análise da estrutura do DataFrame resultante, examinando as colunas, tipos de dados, e verificando a       existência de dados faltantes.
  
  # 3.4 Análise de Atributos Categóricos e Numéricos
  
  • 3.4.1: Explorar e descrever a distribuição dos atributos categóricos no DataFrame.
  
  • 3.4.2: Analisar as propriedades dos atributos numéricos, entendendo sua distribuição e variabilidade.

  # 3.5 Dados Faltantes

  • Identificação de valores ausentes no DataFrame para assegurar a consistência dos dados.

  # 3.6 Análise de Proporção de Entregas por Bairro ou Cidade

  • Cálculo da proporção de entregas realizadas em cada bairro ou cidade do Distrito Federal, com a adição dessas   
    informações ao DataFrame.
  • Análise das proporções para entender a concentração de entregas nas diferentes áreas.
  
  # 3.7 Análise de Tempo de Entrega

  • 3.7.1: Cálculo do tempo médio de entrega para cada região, cidade e bairro. Esta análise ajuda a identificar áreas que       podem estar sofrendo com atrasos e necessitam de otimizações.

  # 3.8 Análise de Capacidade dos Veículos e Volume de Entregas

  • 3.8.1: Cálculo da utilização da capacidade dos veículos, analisando se a frota está sendo utilizada de forma eficiente       ou se há necessidade de ajustes.

  • 3.8.2: Visualização da distribuição da utilização da capacidade dos veículos para identificar padrões e possíveis            otimizações.

  # 3.9 Otimização de Rotas

  • 3.9.1: Cálculo da distância total percorrida por cada veículo para cada entrega, permitindo a análise da eficiência das 
    rotas atuais.

  # 4. Manipulação e Enriquecimento dos Dados

  • 4.2.1 Geocodificação Reversa do Hub: Aplicação de geocodificação reversa para transformar coordenadas geográficas em   
    descrições textuais (cidades e bairros) e enriquecer o DataFrame principal com essas informações.

  • 4.2.2 Geocodificação Reversa das Entregas: Devido à quantidade massiva de dados, a geocodificação reversa foi aplicada       localmente para obter as informações de localização de cada entrega.

  # 5. Análise Gráfica

  # 5.1 Visualização Geoespacial

  • 5.1.1 Mapa do Distrito Federal: Visualização básica do mapa do Distrito Federal.

  • 5.1.2 Mapa dos Hubs: Plotagem dos hubs logísticos no mapa.

  • 5.1.3 Mapa das Entregas: Visualização das entregas realizadas em diferentes regiões.

  • 5.1.4 Visualização das Entregas por Região: Visualização detalhada das entregas segmentadas por região.

   # 5.2 Gráfico de Entregas por Região

   • 5.2.1: Visualização gráfica mostrando a proporção de entregas por região, ajudando a identificar concentrações e            possíveis desbalanceamentos nas operações.

   # 5.3 Mapa de Proporção de Entregas por Cidade

   • 5.3.1: Preparação dos dados geoespaciais para criar um mapa que mostre a proporção de entregas em cada cidade do            Distrito Federal.

   • 5.3.2: Visualização no mapa das cidades com maior densidade de entregas, destacando áreas que podem necessitar de           recursos logísticos adicionais.

   # 5.4 Mapa de Tempo Médio de Entrega por Cidade

   • 5.4.1: Criação de um mapa que ilustra o tempo médio de entrega por cidade, ajudando a identificar regiões onde as           entregas podem estar sendo menos eficientes.

   # 5.5 Mapa de Utilização da Capacidade por Região

   • 5.5.1: Cálculo e visualização da utilização da capacidade dos veículos por região, identificando regiões onde os            recursos logísticos podem estar subutilizados ou sobrecarregados.

   # 5.6 Análise Gráfica da Eficiência das Rotas

   • 5.6.1: Visualização da distribuição das distâncias percorridas pelos veículos, permitindo uma análise detalhada da          eficiência das rotas.

   # Conclusão

    A análise exploratória dos dados logísticos da Loggi forneceu insights valiosos para otimizar a eficiência operacional.     Identificamos padrões de entrega, analisamos a capacidade dos veículos, otimizamos rotas, e visualizamos a distribuição     geográfica das operações. Esses insights permitem à Loggi tomar decisões estratégicas fundamentadas, melhorando a           alocação de recursos e a satisfação do cliente.

    

    

    
    

    

    

  


















  
