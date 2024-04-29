# Projeto de Trainee SPL - 2024.1
Esse projeto visa analisar a capacidade dos Trainees de desenvolver um projeto, num curto espaço de tempo, utilizando a linguagem Rust e aplicando suas noções de lógica de programação, estrutura de dados e orientação a objetos.

## Enunciado
### JOGO DA ENTREGA
O jogo consiste em fazer com que o carteiro (**&**) leve a caixa (**@**) até o ponto desejado (**X**) em um campo que será uma matriz 20x20, onde (**+**) representa um espaço válido...  
Para desenvolver tal projeto vocês terão de usar/desenvolver as estruturas `carteiro`, `caixa`, e `jogo`.
Regras:  
- O carteiro só pode andar um *índice / casa* por iteração  
- Apliquem a ideia de Encapsulamento  
- O código terá uma mapa de exemplo para o teste enquanto estiver em desenvolvimento  
- No dia da apresentação o código será posto em prática com um código diferente   
- Utilize a tecnologia ou algoritmo que achar mais conveniente

## Facilitando sua vida

### Referências
- [Rust Book](https://doc.rust-lang.org/book/)
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
- [Rust Standard Library](https://doc.rust-lang.org/std/)
- [Resumão de Rust em 10 Minutos](https://www.youtube.com/watch?v=br3GIIQeefY)  

*Infelizmente todos os links são em inglês, Rust ainda não é tão popular no Brasil, então há pouco conteúdo em PT-BR*

### Git
É ideal que cada time utilize um repositório no GitHub para desenvolver o projeto. Assim podemos acompanhar o progresso de cada time e ajudar no que for necessário.   
Dê um [fork](https://medium.com/@abnerborgonha/como-fazer-um-fork-de-uma-projeto-no-github-9c78f2899bac) no [repositório do projeto](https://github.com/MarceloRother/marcelorother_trainee_2024_1_rust) e desenvolva o projeto nele.

Uma boa prática é separar uma branch só para desenolvimento, normalmente chamada de `dev` ou `development`. E quando uma nova funcionalidade estiver pronta, você mescla essa branch com a `main`. Evitando problemas de compatibilidade  e mantendo a `main` sempre funcional. É assim que trabalhamos no SPL, então já vai se acostumando.

### Ambiente de Desenvolvimento
Para desenvolver em Rust, é preciso baixar e instalar o compilador da linguagem. Você pode fazer isso através do [site oficial](https://www.rust-lang.org/tools/install).  
Além disso, recomendo utilizar a IDE [Visual Studio Code](https://code.visualstudio.com/) com a extensão [Rust Analyzer](https://marketplace.visualstudio.com/items?itemName=matklad.rust-analyzer) que permite rodar o código dentro do editor, autocomplete e outras funcionalidades.  
Sempre preste atenção nas mensagens do compilador, muitas vezes ele te dá dicas de como resolver um problema. Também recomendo dar uma lida nas utilidades do [Cargo](https://doc.rust-lang.org/cargo/), o gerenciador de pacotes e compilador da linguagem.