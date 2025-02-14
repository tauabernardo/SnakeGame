🐍 Snake Game – Jogo da Cobrinha em Java
O Snake Game é uma implementação clássica do jogo da cobrinha desenvolvida em Java utilizando a biblioteca Swing para a interface gráfica. O objetivo do jogo é controlar a cobra, coletar alimentos para crescer e evitar colisões com as bordas e consigo mesma.

🎮 Funcionalidades
✅ Movimentação da cobra com as teclas W, A, S, D ou Setas do Teclado
✅ Crescimento da cobra ao coletar comida
✅ Contador de pontos
✅ Game over ao colidir com as bordas ou consigo mesma
✅ Interface gráfica simples e dinâmica

🛠️ Tecnologias Utilizadas
Java (JDK 17+)
Swing (JFrame, JPanel, Timer)
📌 Estrutura do Projeto
python
Copiar
Editar
SnakeGame/
│── src/
│   ├── SnakeGame.java  # Classe principal
│   ├── GamePanel.java  # Lógica do jogo e renderização
│── bin/                # Arquivos compilados
🚀 Como Executar
1️⃣ Compile o código:

sh
Copiar
Editar
javac -d bin src/*.java
2️⃣ Execute o jogo:

sh
Copiar
Editar
java -cp bin SnakeGame
💡 Obs.: Caso utilize um ambiente como Eclipse ou IntelliJ IDEA, basta rodar a classe SnakeGame.java.
