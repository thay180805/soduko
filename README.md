Sudoku Game
🎮 Sobre o projeto

Este é um jogo de Sudoku desenvolvido em Java.
O jogo permite que o jogador preencha o tabuleiro, valide jogadas e acompanhe o progresso do jogo.
As regras clássicas do Sudoku são aplicadas: cada número de 1 a 9 deve aparecer uma vez por linha, coluna e região 3x3.


🛠 Funcionalidades

Criação dinâmica do tabuleiro a partir de uma matriz de espaços (Space).

Alteração de valores no tabuleiro (changeValue).

Limpeza de valores (clearValue) e reset completo do tabuleiro.

Verificação do status do jogo: Não iniciado, Incompleto ou Completo.

Detecção de erros (valores incorretos).

Verificação se o jogo foi finalizado corretamente.

🏗 Tecnologias utilizadas

Java 17 (LTS)

IDE: IntelliJ IDEA (ou qualquer IDE Java compatível)

Estrutura orientada a objetos (Board, Space, GameStatusEnum)

📦 Estrutura do projeto
src/
├── br.com.dio.model/
│   ├── Board.java
│   ├── Space.java
│   └── GameStatusEnum.java
├── br.com.dio/
│   └── Main.java
assets/
└── sudoku-demo.gif

🚀 Como executar

Clone o repositório:

git clone https://github.com/seu-usuario/nome-do-repo.git


Abra o projeto na sua IDE Java.

Compile e execute a classe Main.java.

Siga as instruções no terminal para jogar.

🎯 Objetivos do projeto

Praticar programação orientada a objetos em Java.

Aprender a manipular listas, streams e lógica de validação.

Criar um jogo funcional com interface de linha de comando.

🤝 Contribuição

Contribuições são bem-vindas!

Faça um fork do projeto.

Crie sua branch (git checkout -b feature/NomeDaFeature).

Faça commit das suas alterações (git commit -m 'feat: descrição da feature').

Envie para a branch (git push origin feature/NomeDaFeature).

Abra um Pull Request.
