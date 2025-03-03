Escopo do Projeto HydroView

Objetivo do Projeto: Desenvolver um sistema de monitoramento inteligente para reservatórios de água, permitindo acompanhamento remoto e em tempo real dos níveis de água através de uma dashboard dinâmica.

Funcionalidades Principais:
  -Medir o nível da água no reservatório utilizando sensor ultrassônico.
  
  -Armazenar os dados coletados em um banco de dados InfluxDB.
  
  -Exibir os dados em gráficos, indicadores e alertas visuais através do Grafana.
  
  -Permitir acesso remoto às informações coletadas através da integração com Ngrok.
  
  -Garantir comunicação entre os componentes via IoT, utilizando Node-RED para processamento dos dados.

Tecnologias Utilizadas:

  -Arduino para processamento dos dados dos sensores.
  
  -Sensor ultrassônico para medição do nível da água.
  
  -InfluxDB: armazenamento dos dados coletados.
  
  -Node-RED: fluxo de dados e integração IoT.
  
  -Grafana: visualização dos dados coletados por meio de gráficos e dashboards.
  
  -Ngrok: comunicação entre os computadores.
  
Arquitetura do Sistema:

1 - Sensores ultrassônicos conectados ao Arduino medem o nível da água periodicamente.

2 - Os dados são enviados para o servidor onde o Node-RED processa e estrutura as informações.

3 - O InfluxDB registra os dados coletados.

4 - O Grafana exibe os dados em tempo real e de forma intuitiva.

5 - O Ngrok possibilita que os usuários acessem a dashboard de qualquer local com internet.

Critérios de Aceitação: 
  -O sistema deve ser capaz de medir corretamente o nível da água e registrar os dados no InfluxDB.
  
  -A dashboard do Grafana deve exibir os dados de forma clara e atualizada em tempo real.
  
  -A integração via Ngrok deve permitir acesso remoto à dashboard.
  
  -O sistema deve operar de maneira estável e confiável, garantindo a disponibilidade dos dados sem perda de informações.
