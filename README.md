# Prefácio

Este livro vem de um desejo. Um desejo de acessibilidade, simplificação e inclusão. O propósito do livro é ser:&#x20;

* **Acessível**: Para que qualquer pessoa com um fundamento básico de computação possa fazer a adoção da Linguagem.
* **Simplificado**: A linguagem é em suma difícil, sim, ela é. Por que? Porque ela introduz alguns novos conceitos à Programação e abstrai outros de forma inovadora.
* **Inclusivo**: Você está lendo esse livro de maneira totalmente gratuita em Brasileiro (pt-br), no GitBook, sem monetização alguma. Você tem acesso ao código fonte no repositório direto no GitHub, gratuito. ****&#x20;

### Uma linguagem empoderando todos a construir softwares confiáveis e eficientes.&#x20;

Se você pegou algum livro de terceiros da [Linguagem de Programação Rust](https://www.rust-lang.org/pt-BR), provavelmente encontrou a ideia dela de que o propósito dela é ser (de maneira quase que exclusiva proposta por vários outros autores): **uma linguagem para Programação de Sistemas**. O conjunto de itens que entrariam na definição de um **Sistema** são:

* **Sistemas Operacionais** (Windows, Linux, BSD, MacOs, Android, iOS, etc).
* **Drivers** para dispositivos (Impressoras, teclados, mouses, etc).
* **Bancos de Dados** (MySQL, PostgreSQL, MongoDB, Redis, etc).
* **Criptografia e Redes** (blockchains, protocolos de rede - de diversos tipos, até mesmo o modelo OSI ou algo análogo ao Bluetooth - etc).
* Jogos (Visto que precisam de extrema Eficiência porque trabalham com muit



&#x20;

Far-se-á necessário deixar mais do que claro, a definição do que é uma linguagem para a  Programação de Sistemas. é relativo à algum tipo de software que roda sobre as seguintes restrições:&#x20;

1. Seja Seguro (Onde não haja: [condições de corrida](https://pt.wikipedia.org/wiki/Condi%C3%A7%C3%A3o\_de\_corrida), [vazamentos de memória](https://pt.wikipedia.org/wiki/Vazamento\_de\_mem%C3%B3ria), [etc](https://pt.wikipedia.org/wiki/Rust\_\(linguagem\_de\_programa%C3%A7%C3%A3o\))).
2. Energeticamente Eficiente (Onde não haja desperdício energético por outros como por exemplo, um coletor de lixo que roda paralelamente).
3. Rápido (Isto é, que seja otimizada - ou que permita -  acesso ao ["Baixo Nível"](https://minutodaseguranca.blog.br/importancia-da-linguem-de-programacao-de-baixo-nivel/) onde o programador, caso queira, possa fazer controle da inversão de um Byte na memória para otimizar um ganho de "tempo" em um ciclo da CPU).&#x20;
4. Previsível e Estável (Onde haja, sob ambiente ideal, em uma [máquina de turing](https://pt.wikipedia.org/wiki/M%C3%A1quina\_de\_Turing) a execução de um mesmo código infinitas vezes de maneira que o resultado dele seja completamente predito - rust também implementa de maneira nativa o conceito de Programação funcional & testes automatizados para cumprir estes propósitos ante-citados).





