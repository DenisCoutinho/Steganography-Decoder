# Decodificador-Esteganografia

O termo esteganografia1 deriva da junção das palavras gregas estegano que significa “esconder ou mascarar”, e grafia, que significa “escrita”. 

Portanto, esteganografia pode ser compreendida como a arte de esconder informações, tornando-as ocultas, assim como a criptografia. O objetivo desta técnica é que esses dados não sejam percebidos por terceiros, ou seja, a presença de mensagens escondidas dentro de arquivos é simplesmente desconhecida.

Somente o receptor da mensagem tem conhecimento de sua existˆencia, assim como da maneira como extraí-la. Apesar de parecer, a esteganografia e a criptografia são duas áreas com objetivos bastante diferentes. Enquanto o segundo tem o propósito de impedir que as pessoas saibam o conteúdo de uma mensagem, o primeiro se baseia em evitar que as pessoas saibam que a mensagem escondida existe. 

Ou seja, na criptografia, os receptores sabem da existência das mensagens, porém não conseguem, a princípio, lê-las, a esteganografia tenta fazer com que os receptores não percebam que há uma mensagem naquele meio (imagem, texto, etc.).

Existem várias formas de esconder mensagens ou arquivos em imagens. Uma das técnicas possíveis é modificar alguns bits (menos relevantes) dos pixels da imagem, com as informações que se quer esconder. Por exemplo, a modificação do bit menos significativo de uma banda (red) de um pixel de uma imagem colorida nnão é perceptível ao olho humano. 

A esteganoanálise dessa modificação, no entanto, não é difícil de se realizar a partir da comparação do arquivo original e do arquivo modificado. O ruído, calculado como a diferen¸ca desses dois arquivos é a mensagem codificada. 

O objetivo desse trabalho é explorar os conceitos de cores e de codificação e decodificação utilizados nos formatos de imagens.

# Instrução de Uso:

O programa é chamado em linha de comando da seguinte forma:
./decode <nome=arquivo=imagem>[.ppm]

Por exemplo:

./decode porto

O programa gera o arquivo que está codificado na imagem, na mesma pasta onde o decodificador for executado

