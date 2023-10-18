# Pipeline-de-ETL
# Desafio de projeto do Cuso DIO no qual exploramos processos de Extração, Transformação e Carregamento de dados

O desafio incentiva a utilização de Inteligência Artificial para criação de mensagens personalizadas que serão direcionadas a cada usuário selecionado. No entanto, o cumprimento desse projeto não está condicionado a essa opção. Desta forma, neste momento, o projeto será focado em processos mais simples, como o uso de arquivo .csv e banco de dados. 

Contudo, essa não será a versão final, pois em breve farei alterações para empregar a IA, a fim de deixar o processo mais dinâmico e independente.

A Extração de dados se deu com a utilização e criação de novos usuários consumindo o endpoint GET https://sdw-2023-prd.up.railway.app/users/{id} (API da Santander Dev Week 2023)

A planilha de identificação dos usuários (1SDW2023.csv) – anexa- foi atualizada com o UserID de cada usuário selecionado. 
Foi realizada uma requisição  GET com a importação da biblioteca panda extraindo corretamente o número de cada nova ID.

A transformação/ limpeza dos dados, podem ser realizadas com análise de banco de dados que possibilita observar o perfil e histórico de cada cliente bancário, com o intuito de personalizar ainda mais as mensagens direcionada a eles, o que promove um impacto mais positivo desse marketing.

A atualização também utilizará o banco de dados para registrar as mensagens enviadas e todas ações que foram tomadas, bem como, registrar os impactos percebidos com a ação.
