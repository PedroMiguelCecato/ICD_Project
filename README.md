# GamesData
### Projeto desenvolvido como conclusão da cadeira de Introdução á Ciência de Dados, durante a graduação no curso de Ciência de Dados e Inteligência Artificial.<br>UFPB - 2023.2
<br><br><br>

### 🧠 Autores:
<br>
<a href="https://github.com/PedroMiguelCecato">Pedro Miguel Cecato Valões</a>
<br>
20230021831
<br><br>

<a href="https://github.com/Gusttavoafonso">Gustavo Afonso da Silva</a>
<br>
20230014130
<br><br><br>

### ✍️ Ao final desse projeto, poderemos responder:
<br>
- Qual empresa lançou/vendeu mais jogos?
<br>
- Quais os jogos de uma determinada companhia foram mais vendidos?
<br>
- Em qual região uma determinada corporação vendeu mais?
<br>
- Qual a opinião dos usuários/analistas sobre os jogos de uma deternminada empresa?
<br>
- Qual jogo foi avaliado de forma mais positiva?
<br>
- Como foi a avaliação dos jogos de uma determinada empresa ao longo dos anos?
<br><br>

Faremos uma análisde minuciosa de todos esses fatores, dentre outros, com o objetivo de coletar informações suficientes sobre a venda de jogos de console de modo que o leitor possa tirar suas próprias conclusões.
<br><br><br>

### 📁 Dataset utilizado:
<br>
<a href="https://www.kaggle.com/code/praveensaik/video-game-sales-analysis-eda/notebook">Video Game Sales</a>
<br><br><br>

### 🎮 Evolução dos jogos:
<br>
&nbsp;&nbsp;Atualmente, a indústria dos videogames é uma potência global, movimentando cerca de US$100 bilhões. Essa extraordinária popularidade é justificada pela longa trajetória dos videogames ao longo de décadas, abrangendo uma ampla variedade de plataformas. Desde os clássicos sistemas de arcade até os modernos consoles domésticos, dispositivos portáteis e até mesmo smartphones. À medida que novas tecnologias se integram em diversos dispositivos, essa mesma evolução impulsiona os jogos eletrônicos, proporcionando aos usuários uma vasta gama de novas possibilidades e recursos para explorar.
<br><br>

&nbsp;&nbsp;Embora os videogames sejam encontrados hoje em lares por todo o mundo, eles realmente nasceram nos laboratórios de pesquisa científica. Em 1940, na New York World Fair, mais de 50 mil pessoas jogaram um game de matemática contra o computador que ganhou quase 90% das vezes. Em 1952, o professor britânico A.S. Douglas criou o OXO, também conhecido como zeros e cruzes ou jogo da velha, como parte de sua tese de doutorado na Universidade de Cambridge. Um pouco adiante, em 1958, William Higinbotham criou Tennis for Two em um grande computador analógico e tela de osciloscópio conectado no Laboratório Nacional de Brookhaven em Upton, Nova York.
<br><br>

&nbsp;&nbsp;O Spacewar!, criado em 1962 por Steve Russell, do Massachusetts Institute of Technology, foi o primeiro videogame que pode ser jogado em várias instalações de computador. Já em 1967, finalmente, foi criado o primeiro jogo eletrônico para ser usado em casa, que se parece com o videogame que conhecemos hoje, Brown Box trazia até seis jogos diferentes, tendo sido amplamente aceito entre 1972 e 1975. Na década de 70, os jogos arcade se espalharam pelos Estados Unidos, tornando-se populares entre os usuários que queriam alcançar pontuação máxima entre as principais máquinas, como Space Invaders, Pong, Donkey Kong e Pac-Man.
<br><br>

As maiores evoluções dos jogos eletrônicos estão ligadas principalmente com o desenvolvimento tecnológico dos computadores. A microeletrônica proporcionou um aumento muito grande no poder computacional ao longo das últimas décadas:
<br>
&nbsp&nbsp&nbs&nbs - 1ª Geração (1972 a 1978): o lançamento do primeiro videogame doméstico comercial, o Magnavox Odyssey, seguido de outros games, como Pong, marcou a primeira geração de consoles de mesa;
<br>
&nbsp&nbsp&nbs&nbs - 2ª Geração (1978 a 1984): é marcada pelo início da era dos cartuchos de videogame, permitindo o fortalecimento das empresas deste mercado. O período dos arcades era visto como a era de ouro dos videogames. Os consoles de segunda geração foram definidos pelo microprocessador;
<br>
&nbsp&nbsp&nbs&nbs - 3ª Geração (1984 a 1990):  depois do crash dos videogames de 1983, companhias japonesas apresentaram os videogames de 8 bits, buscando retomar um mercado destruído e dominado pelos arcades. Nesta geração, empresas como Nintendo e Sega buscam reafirmação;
<br>
&nbsp&nbsp&nbs&nbs - 4ª Geração (1990 a 1996):  também conhecida como a guerra dos consoles, essa geração foi marcada pelo advento dos consoles de 16 bits e pela disputa das empresas, que conduziam a estratégia com franquias e ações de marketing agressivas;
<br>
&nbsp&nbsp&nbs&nbs - 5ª Geração (1996 a 1999): termina a era dos consoles de 32 e 64 bits, encerrando o ciclo da evolução dos jogos eletrônicos orientada por arquitetura de processador. Essa geração é marcada pela manutenção de franquias e entrada de novos fabricantes, como a Sony e a mídia de CD;
<br>
&nbsp&nbsp&nbs&nbs - 6ª Geração (1999 a 2004): os cartuchos saem de cena e o DVD passa ser o novo padrão dos consoles de mesa, voltando o foco para os jogos online e as convergências tecnológicas. Os consoles passam a oferecer um processamento com performance comparável aos computadores pessoais;
<br>
&nbsp&nbsp&nbs&nbs - 7ª Geração (2004 a 2011): na tentativa de se destacar e oferecer uma experiência única para os usuários, os consoles de mesa se tornam máquinas de performance de 128-bits e total conectividade com serviços de internet. Novas formas de interação com os usuários são pensadas para engajar os usuários;
<br>
&nbsp&nbsp&nbs&nbs - 8ª Geração (2012 até 2020): capacidade de armazenamento (blu-ray), conectividade total, exclusividade, experiências com novas formas de interação e potência em processamento;
<br>
&nbsp&nbsp&nbs&nbs - 9ª Geração (2020 até hoje): atualmente, essa geração oferece tudo o que um usuário espera de um console de mesa, imagens mais realistas, menor tempo de carregamento dos jogos. Em termos de estrutura, a arquitetura dos consoles da nona geração se parece com a dos computadores dedicados a jogos.
<br><br>

&nbsp&nbsp&nbs&nbs Como vimos até aqui, a evolução dos jogos eletrônicos tem sido orientada pelo avanço da tecnologia e pelo surgimento de novas ferramentas. Com a implantação de soluções inovadoras, certamente os consoles irão proporcionar experiências ainda mais divertidas e surpreendentes para os usuários.
