# pure-cpp-sfml-sprite-animation-extension
its a class to animate sprites in your c++'s sfml projects

/**
  @Jozuteomo
  
  just work with c++/sfml
*/
adicione essa classe no seu projeto, e utilize as seguintes funções

--construtor
[

  leva parametros de:
  - pointer para a textura **que no caso deve ser criada antes de chama-la
  - vector2u para as coordenadas de largura e altura da textura
  - switchTime, valor para o tempo (em segundos) de demora de imagem para imagem

]

--update
[

  leva parametros de:
  - int row, (seguindo a base de que o 1º é 0), posicao da linha da animacao
  - float deltaTime, tempo de demora entre imagens

]

/**

  um objeto sf::Clock deve ser criado antes da aplicacao de deltaTime

*/

///////////////////////////////////////////////////////////////////////
