Esse repositorio é destinado ao nosso primeiro sistema de jogo criado por meio da linguagem C.

O nosso projeto de jogo é focado em criar um jogo constituido de 3 subjogos que podem ser acessados e jogados pelo usuario, mediante a descisões do usuario, o que inclui a escolha do jogo a ser jogado pelo menu, no qual inclui estes games e a opção de sair, que fecha o jogo prinicpal, ou seja, finaliza o codigo inteiro:

 1-Perguntas e respostas
 
 2-Cobra na caixa 
 
 3-Gousmas war
 
 4-Sair
 
 

 Cada minigame apresenta suas proprias características:
 
 *1)Perguntas e respostas:*
 
   Nesse jogo, há 5 perguntas e 4 alternativas para cada uma das questões.
   
   O jogador precisa ler o texto de cada pergunta e digitar a letra da alternativa que acredita ser a resposta correta, então o sistema dirá se a escolha está certa ou errada.
   
   O jogo segue nesse esquema até a útilma pergunta ser lida e respondida, considerando que cada questão só pode ser respondida uma vez por partida e sempre que for dada uma resposta segue para o proximo enunciado independentemente se ela está incorreta ou não.

 *2)Cobra na caixa:*
 
   Nesse jogo, o seguinte contexto: dois exploradores estão perdidos numa tumba egipicia e ,na sala atual em que se encontram, existem 7 vasos, dentre os quais um armazena uma cobra e o outro um botão.
   
   No jogo em si, os jogadores são os exploradores e, no inicio do jogo, cada um deve escolher o nome do seu personagem dentre uma lista de 5 nomes predefinidos, então o sistema escolhe qual dos dois participantes joga primeiro. Cada um dos players deve escolher um entre os 7 compartimentos, se ele estiver vazio, o jogo segue normalmente alternando entre os turnos dos jogadores para abrir os recipientes, mas, caso alguem encontre a cobra, este será automaticamente eliminado do jogo sendo considerando perdedor, e se encontrar o botão, ele será considerado o ganhador do jogo, sendo que em ambas estas duas situações esse subjogo é encerrado, mesmo se o outro termo não for encontrado. 
   
   Além disso, vale ressaltar o jogador não pode selecionar o mesmo um vaso já aberto anteriormente.
    
 *3)Gousma war:* 
 
   Nesse jogo, o player 1 e player 2 disputam entre si, mediante as gousma, que são entidades.
   Cada jogador começa com 2 gousmas e cada gosma possue 2 pontos de furia.
   No inicio, o jogador tem duas opções atacar ou distribuir sua furia: 
   
Atacar:

 - Ao selecionar "atacar", o jogador deve escolher a sua gosma que atacará e a gosma que será atacada.
    
 - Ao atacar uma das gousmas do outro jogador, a furia que a atacante possue foi adicionada a atacada e, se a gousma ficar com mais de 5 pontos de furia, ela vai ser destruida e não pode mais atacar ou ser atacada enquanto não tiver pelo menos 1 ponto de furia.

Distribuir:

 - Ao selecionar "distribuir", o jogador atual tem a possibilidade passar a furia que possue em uma de suas gousmas para a outra, podendo reviver a que estiver morta ou aliviar o peso de uma levada furia em alguma delas.

 Além disso, vale ressaltar que só pode ser executada uma dessas ações por turno de jogador e um dos jogadores vence quando o outro tiver a furia de suas 2 gousmas igual a zero, ou seja, estejam destruidas.

  
   
Ao fim de todos os subjogos, são apresentadas ao jogador a opção de executar o jogo atual novamente ou de sair e retornar ao menu principal para escolher algumas das outras alternativas.




*°Observação sobre o codigo:*

 - No jogo cobra na caixa, o chat gpt foi utlizado principalmente em partes lógicas como em criar uma variavel que fosse aleatória para as cobras, com isso o chat foi dando mais sujestões para melhorar o código e otimiza-lo, as quais fora acatadas, desde o nomes serem feitos com matrizes e strcpy, ou a escolha dos jogadores serem feitas com 1- a variavel do jogador.


           Esse projeto foi executado por Bernardo Rodrigues e Diego Viana Pereira de Araújo, CC1MA.
