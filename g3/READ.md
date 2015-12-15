Algoritimo

MAIN: chama a funcao roda
-----------------------
RODA:chama as funcoes
atualiza e desenha
-----------------------
ATUALIZA:chama funcao
bloco.atualiza e obstaculos.atualiza
----------------------
DESENHA:
// fundo
  cor:"#50beff"
  tamanho:
  (0, 0, LARGURA, ALTURA);
  ,,,,,,,,,,,,,,,,,,,,
  //score
  cor:"#000000";
  local onde fica:
  30, 68
  tem escrito: jumps
  estilo:"15px Tahoma"
  ,,,,,,,,,,,,,,,,,,,,
// record
 quadrado:
 cor: "yellow"
 letra "50px Arial"
,,,,,,,,,,,,,,,,,,,,
chama funcao:
obstaculos.desenha
chao.desenha
bloco.desenha
