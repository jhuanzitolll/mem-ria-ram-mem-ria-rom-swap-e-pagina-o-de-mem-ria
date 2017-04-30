#Tipo de memórias 

## Memória RAM

A memória RAM é um tipo de tecnologia que permite o acesso aos arquivos armazenados no computador. Diferentemente da memória do HD, a RAM não armazena conteúdos permanentemente. É responsável, no entanto, pela leitura dos conteúdos quando requeridos. Ou seja, de forma não-sequencial, por isso, a nomenclatura em inglês de Random Access Memory (Memória de Acesso Aleatório). 
Para simplificar a lógica por trás da função da memória RAM, é possível fazer uma analogia com uma mesa de estudos, onde se reúne todo o material necessário para realizar os deveres de casa: como canetas, lápis, caderno e livros. Os materiais seriam os arquivos e a memória RAM, a mesa, onde tudo se reúne e o trabalho é feito.
Sendo assim, a memória RAM pode ser entendida como um espaço temporário de trabalho, pois, após a tarefa ser realizada, os arquivos (material de estudos) são retirados da memória (mesa) e mantidos no HD (armário).
Como funciona
Assim como a mesa, quanto maior a memória RAM, maior sua capacidade de trabalho. Mas a capacidade da mesa é medida em área. Quanto maior a área da mesa, mais livros cabem e mais rapidamente se faz o trabalho. Já a capacidade da memória RAM, mede-se pelo fluxo de bits suportados nas operações.
Ou seja, para se acessar uma grande quantidade de memória  no HD de uma só vez, como muitos programas atuais exigem, é necessário uma grande quantidade de memória RAM. São estes, portanto, os megabites ou gigabites que aparecem nas configurações.
A memória RAM é um chip semelhante a um micro-processador, composto por milhões de transistores e capacitores. O capacitor é uma peça capaz de armazenar elétrons. Quando ele está carregado, o sistema faz uma leitura com base no famoso código binário de “zeros e uns”. Cada leitura dessa em zero ou um significa um bit de informação. Essa leitura é feita de forma muito rápida, são muitas em poucos milésimos de segundos. É assim que a memória RAM processa todas as ações executadas pelo usuário.
Largura e velocidade do barramento
Outras características que influenciam na capacidade de processamento da memória RAM são a largura e a velocidade do barramento, que é um conjunto de “fios” responsáveis pela conexão da memória com os outros componentes.
A largura nos diz o número de bits que podem ser enviados ao CPU simultaneamente. A velocidade é o número de vezes que esse grupo de bits pode ser enviado a cada segundo.
A memória comunica-se com o CPU, trocando dados, e completa o que se conhece como ciclo de barramento. É esse período que apresenta o desempenho da memória que, pode ser de 100MHz e 32bits, por exemplo. Isto singnifica que tal memória é capaz de enviar 32bits de dados ao processador 100 milhões de vezes por segundo. No entanto, existe um efeito chamado latência, que atrasa a taxa de transferência de dados de forma significativa quando se envia o primeiro bit.
Ao se comprar uma memória deve-se ficar atento para essa questão da taxa de transferência. Não adianta a memória  ter uma frequência alta e a frequência do sistema ser menor, pois a taxa do sistema vai limitar a da memória RAM. Portanto, para um sistema que rode a 100MHz e 32bits, compre uma memória com os mesmos aspectos.

## Memória ROM

Aqueles que nunca ouviram falar da ROM certamente conhece um primo próximo desse tipo de memória, o CD-ROM, uma mídia ótica que permite apenas a leitura de dados. Ou seja, você não pode gravar arquivos em um CD-ROM, apenas executar ou visualizar o que já estiver nele.
Basicamente, essa é a função da memória ROM: oferecer dados apenas para leitura. Normalmente, a ROM é utilizada para armazenar firmwares, pequenos softwares que funcionam apenas no hardware para o qual foram desenvolvidos e que controlam as funções mais básicas do dispositivo.
Na ROM de uma calculadora, por exemplo, podemos encontrar as rotinas matemáticas que o estudante pode realizar ao usá-la. Já no caso de celulares, normalmente as ROMS carregam o sistema operacional e os softwares básicos do aparelho.

### SWAP: Uma memória virtual para o seu Computador

Se você é leigo em sistemas operacionais cabe fazer uma citação que pode parecer obvia para quem já manja um pouco do assunto; dentro do seu computador existem chips encaixáveis com circuitos integrados soldados a ele, a esses dispositivos damos o nome genérico de "pente de memória", você pode ver o exemplo de um na imagem abaixo.Não vou entrar em muitos detalhes técnicos porque o assunto do artigo já é técnico o suficiente, as memórias RAM, como esta da imagem acima, podem ser de tamanhos variados seguindo dois modelos básicos, um para Desktop (como esta acima) e outro um pouco menor usado normalmente em portáteis como Notebooks e Netbooks, independente do seu tamanho e capacidade (medida em Giga Bytes) as memórias tem as mesmas funções, armazenar dados enquanto o processador trabalha com os mesmos.

Assim que você liga o seu computador o sistema operacional é carregado para a memória RAM afim de possibilitar a sua entrada no Facebook para duelar com os seus dragões.
Mas porque eu falei de memória RAM?

Entonces, a memória SWAP tem uma ligação quase familiar com a memória RAM, uma ajuda a outra, para ser mais claro, a memória SWAP costuma entrar em ação quando a memória RAM não consegue "dar conta do recado".

Em computadores atuais isso é bem mais raro de acontecer, computadores com 4GB de RAM ou mais raramente usam a memória SWAP, como você pode ver abaixo no meu computador, dos 1,9 GB de SWAP apenas 1,5 MB está sendo utilizado!

#### Paginação

A paginação permite que o programa possa ser espalhado por áreas não contíguas de memória. Com isso, o espaço de endereçamento lógico de um processo é dividido em páginas lógicas de tamanho fixo e a memória física é dividida em páginas com tamanho fixo, com tamanho igual ao da página lógica. Nisso, o programa é carregado página a página, cada página lógica ocupa uma página física e as páginas físicas não são necessariamente contíguas. O endereço lógico é inicialmente dividido em duas partes : um número de página lógica (usado como índice no acesso a tabela de páginas, de forma a obter o número da página física correspondente) e um deslocamento dentro da página. Não existe fragmentação externa, porém existe fragmentação interna (Ex: um programa que ocupe 201kb, o tamanho de página é de 4 kb, serão alocadas 51 páginas resultando uma fragmentação interna de 3kb). Além da localização a tabela de páginas armazena também o bit de validade, (1 ou TRUE) se a página está na memória (0 ou FALSE) se a página não está na memória. E a transferência das páginas de processo podem ser transferidas para a memória por demanda, levando apenas o que é necessário para a execução do programa ou por paginação antecipada, onde o sistema tenta prever as páginas que serão necessárias à execução do programa.
