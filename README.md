# Campo Minado em Java com Swing

Este é um projeto de Campo Minado implementado em Java com a biblioteca Swing. O Campo Minado é um jogo clássico em que o jogador deve desvendar as células de um tabuleiro, evitando as minas escondidas em algumas delas.

## Regras de Jogo

As regras básicas do Campo Minado são as seguintes:

1. O jogo é jogado em um tabuleiro retangular, composto por células.
2. Algumas células contêm minas ocultas, enquanto outras estão vazias.
3. O objetivo do jogador é desvendar todas as células vazias sem revelar uma mina.
4. Ao revelar uma célula, pode-se encontrar um número, que indica a quantidade de minas nas células vizinhas.
5. Se uma célula com uma mina for revelada, o jogo termina imediatamente e o jogador perde.
6. O jogador pode marcar células suspeitas de conter minas para ajudar a lembrar quais células evitar.
7. O jogo é ganho quando todas as células seguras são reveladas e todas as minas são marcadas corretamente.

## Requisitos
Para executar o jogo, você precisa ter instalado:

Java Development Kit (JDK) 13 ou superior.
Uma IDE de sua escolha, como Eclipse, IntelliJ, NetBeans ou VSCODE.

## Como Executar

Siga as etapas abaixo para executar o jogo:

1. Clone o repositório ou faça o download do código-fonte do projeto.
2. Abra sua IDE e importe o projeto.
3. Certifique-se de que as bibliotecas Swing estão configuradas corretamente.
4. Compile e execute o arquivo `TelaPrincipal.java`.

## Como Jogar

Ao executar o jogo, você verá um tabuleiro vazio. Clique nas células para revelá-las. O objetivo é evitar as minas. Se você revelar uma mina, o jogo terminará imediatamente.

As células reveladas podem conter um número, que indica a quantidade de minas nas células vizinhas. Use essas informações para evitar as minas e continuar explorando o tabuleiro.

Para marcar uma célula suspeita de conter uma mina, clique com o botão direito do mouse. Isso ajudará você a se lembrar de quais células você suspeita que contenham minas.

Continue jogando até revelar todas as células seguras ou até identificar todas as minas corretamente. Se conseguir revelar todas as células seguras, você vence o jogo.

## Como foi Desenvolvido

O Campo Minado foi desenvolvido em Java, utilizando a biblioteca Swing para a criação da interface gráfica. O jogo é composto por diversas classes que gerenciam a lógica do jogo, como a criação do tabuleiro, o posicionamento das minas, a revelação das células e a contagem das minas vizinhas.

Além disso, foram implementados métodos para tratar as interações do jogador com o tabuleiro, como a identificação dos cliques nas células e o gerenciamento das marcações de minas suspeitas. A interface gráfica foi projetada de forma intuitiva, permitindo uma experiência de jogo agradável.

## Conclusão

O Campo Minado em Java com Swing é um projeto divertido e desafiador. Ele permite que os jogadores testem suas habilidades de lógica e raciocínio, enquanto tentam evitar as minas e revelar todas as células seguras.

O uso da biblioteca Swing facilita a criação de uma interface gráfica interativa e amigável, tornando o jogo mais atraente para os jogadores. O projeto também oferece a possibilidade de expansão e melhorias, possibilitando que

 outros desenvolvedores contribuam com novas funcionalidades.

Divirta-se jogando Campo Minado e sinta-se à vontade para contribuir com o projeto!