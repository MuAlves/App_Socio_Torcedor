# App_Socio_Torcedor

🧾 Projeto – Aplicativo de Controle de Carteirinha do Sócio Torcedor

Linguagem utilizada: Java
Conceitos aplicados: Programação Orientada a Objetos, Interface, Polimorfismo, Estruturas de Decisão

🎯 Objetivo do Projeto
Desenvolver um aplicativo simples para controle de sócios torcedores, com foco na verificação de dados, identificação de torcedores, associação a times e estádios, além do cálculo de premiações com base no desempenho esportivo.

🧠 Lógica Implementada
Utilização de polimorfismo por meio de uma interface para o sócio torcedor, permitindo diferenciação de comportamentos com base na categoria ou nome do torcedor.

Implementação de estruturas de decisão com dois blocos switch:

Um para o controle dos times (10 times disponíveis)

Outro para o controle dos estádios (10 estádios disponíveis)

Permite expansão do projeto para incluir mais clubes e arenas, conforme necessidade.


🧪 Funcionamento (Exemplo de Execução)
text

Digite o nome do Torcedor: Fulano
Nome do Torcedor: Fulano
Número da identificação do torcedor: 39
Categoria do Sócio Torcedor é: N

Digite o nome do Time: santos
Estádio: Vila Belmiro (Santos)

Número de jogadores do time: 24
Valor em caixa: 28.687.789

Desempenho:
- Libertadores: 1º lugar
  Premiação: 93 milhões

- Copa do Brasil: 3º lugar
  Premiação: 8 milhões

- Campeonato Brasileiro: 11º lugar
  Premiação: 19 milhões

  
🔧 Recursos Técnicos Utilizados
Classes e interfaces para modelagem de torcedor, time e estádio

Utilização de Scanner para entrada de dados

Uso de switch-case para:

Selecionar o time entre 10 opções

Selecionar o estádio correspondente

Lógica condicional para:

Determinar a categoria do sócio

Calcular premiações baseadas na colocação

Impressão de todos os dados no console

💡 Potencial de Expansão
Cadastro com interface gráfica (JavaFX ou Swing)

Persistência de dados em banco (SQLite, MySQL)

Mais clubes, estádios e categorias de sócio

Integração com APIs de futebol
