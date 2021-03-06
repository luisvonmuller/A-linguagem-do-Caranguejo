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
* **Jogos e Simulações Científicas** (Visto que precisam de extrema Eficiência porque trabalham com muitos detalhes físicos e interações em tempo real - ou seja - não podemos desperdiçar um ciclo, um byte).

Far-se-á necessário deixar mais do que claro: A definição do que é uma linguagem para a  Programação de Sistemas, é relativo à algum tipo de software que roda sobre as seguintes restrições:&#x20;

1. **Seguro** (Onde não haja: [condições de corrida](https://pt.wikipedia.org/wiki/Condi%C3%A7%C3%A3o\_de\_corrida), [vazamentos de memória](https://pt.wikipedia.org/wiki/Vazamento\_de\_mem%C3%B3ria), [etc](https://pt.wikipedia.org/wiki/Rust\_\(linguagem\_de\_programa%C3%A7%C3%A3o\))).
2. **Energeticamente Eficiente** (Onde não haja desperdício energético por outros como por exemplo, um coletor de lixo que roda paralelamente).
3. **Rápido** (Isto é, que seja otimizada - ou que permita -  acesso ao ["Baixo Nível"](https://minutodaseguranca.blog.br/importancia-da-linguem-de-programacao-de-baixo-nivel/) onde o programador, caso queira, possa fazer controle da inversão de um Byte na memória para otimizar um ganho de "tempo" em um ciclo da CPU).&#x20;
4. **Previsível e Estável** (Onde haja, sob ambiente ideal, em uma [máquina de turing](https://pt.wikipedia.org/wiki/M%C3%A1quina\_de\_Turing) a execução de um mesmo código infinitas vezes de maneira que o resultado dele seja completamente predito - _Rust_ também implementa de maneira nativa o conceito de Programação funcional & testes automatizados para cumprir estes propósitos ante citados).

Agora que você leu o conceito, faça à si mesmo a seguinte pergunta:&#x20;

> "Por qual motivo, razão, circunstância meu Aplicativo, Site ou API não pode ser tudo isso?"
>
> * Alguma personalidade do autor enquanto escrevia, 1 de dezembro, 18:12:42.

Então, para melhor decorrer sobre essa ideia, vamos supor que você está implementando um: **Aplicativo Web para controlar o fluxo de caixa no Bar do Fulano.**&#x20;

#### Um Lado da moeda.&#x20;

Se você adotar: _**Java**_, _**TypeScript**_ ou _**C#**_ para a implementação do software, tentando cumprir cada um dos itens acima você **obrigatoriamente não cumpre o segundo**. Todas essas linguagens, em si, possuem **um coletor de lixo** que roda em paralelo coletando "pedaços" da memória que já caíram em desuso pelo processo vigente, isto é: "A Thread".&#x20;

_Permita-se ser introduzido a isto sobre isso no_ [_<mark style="color:blue;">**Podcast**</mark>_](https://hipsters.tech/rust-hipsters-ponto-tech-276/) _**Hipsters.Tech** onde falam sobre **Rust.** E porque linguagens como Go apesar de Cumprirem o papel de serem seguras no paralelismo não são energeticamente eficientes/performáticas._&#x20;

#### Outro Lado da moeda.

Noutro lado da moeda, temos Linguagens como: **C, C++, Assembly**. Elas também não cumprem "sozinhas" o requisito número um (a menos que você seja o Ronaldo na copa de 2002, ou seja, bata um bolão nela). Elas não são totalmente seguras no paralelismo (isto é, depende intrinsecamente da sua capacidade de implementação e nada disso é garantido pela linguagem em si nativamente).

Ainda neste lado da moeda esta: Elas são extremamente complexas. Ou seja, se você quiser fazer algo grandes com elas, você precisa de bons fundamentos teórico computacionais para que implemente de maneira efetiva os requisitos supracitados.&#x20;

Nessa complexidade agregada, há um custo, sua **produtividade obrigatoriamente cai**. &#x20;

#### A moeda de Schrödinger...

Rust é a moeda de Schrödinger, cabo.&#x20;

