# IA para gereção de mensagem para um usuário

## Objetivo:
O projeto visa integrar e analisar dados de usuários a partir de arquivos JSON e CSV, com o objetivo de recuperar e agregar novos dados.

### Extract:
Para esta etapa foram criados 2 arquivos para possibilitar o desenvolvimento do projeto, sendo eles, "SDW2023.json" contém informações detalhadas dos usuários e "usuarios.csv" contendo o ID de cada usuário'. Posteriormente essas informações são armazenadas em suas respectivas variáveis para que possam ser trabalhadas.

### Transform:
Na 2ª e última etapa, com o auxílio da API da OpenAI, é criada uma função para solicitar a criação de mensagens personalizadas para cada usuário sobre a importância dos investimentos. Ao final disto, as mensagens geradas são armazenadas em seus respectivos usuários no arquivo SDW2023.json.

### Tecnologias e Ferramentas Utilizadas:
* Python: Linguagem de programação principal para manipulação de dados e integração com APIs.
* Pandas: Utilizado para ler e processar dados do arquivo CSV.
* JSON: Formato de dados para armazenar e transferir informações.
* OpenAI API: Usada para gerar mensagens personalizadas sobre investimentos.
  
### Aplicações e Benefícios:
* Automatização de Processos: O projeto demonstra como automatizar a recuperação e análise de dados de usuários de forma eficiente.
* Personalização: A geração de mensagens personalizadas adiciona um nível de personalização que pode ser usado para engajamento com os usuários.
* Habilidade Técnica: Mostra competência em manipulação de dados, integração de diferentes fontes de dados e uso de APIs.
* Esse projeto combina habilidades de manipulação de dados com o uso de tecnologias avançadas, evidenciando a capacidade de trabalhar com dados em grande escala e gerar insights valiosos.
