A) O docker começou a baixar (pull) os arquivos necessáriops na máquina para poder efetuar o comando (que foi realizado logo após o Pull automático).
B) O comando docker ps retorna informações e dados de imagens que estão em execução no momento. Neste caso, somente as colunas das informações (ID, IMAGE, COMMAND etc).
O comando docker ps -a, mostra na íntegra as informações da imagem.  Neste caso, ID: b7ed37ee198e, IMAGE: hello-world etc.
RESUMO: Um comando mostra o que uma imagem contém, mas sem mostrar as informações. O comando docker ps -a mostra os dados em tempo real ou comando já rodados.
C) Mostra qual imagem foi acionada anteriormente, seu ID, uso no DISK e tamanho do conteúdo.
D) A imagem é como se fosse uma classe Java. E o conteiner um objeto.
Um é um molde de bolo por exemplo, e outro é o bolo em si a partir do molde

 