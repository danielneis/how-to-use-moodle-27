---
layout: page
---

O que é o Moodle
--------------

Moodle é um Ambiente Virtual de Ensino e Aprendizagem (AVEA),
utilizado por universidades, escolar comunitárias, escolas primárias, empresas
e também por instrutores independentes para incrementar seus cursos com tecnologias web.

Mais de 30.000 (trinta mil) organizações educacionais ao redor do mundo usam o Moodle
para fornecer cursos à distância e também para apoiar cursos presenciais.
O Moodle está disponível gratuitamente na web (https://moodle.org) de forma que qualquer
pessoa pode copiar e instalar. Mais instruções sobre isso, logo a frente, neste prefácio.

O nome Moodle tem dois significados. Primeiro, um acrônimo (o que não é, hoje em dia?) para
Modular Object-Oriented Dynamic Learning Environment (ou, em português, Ambiente de aprendizagem
dinâmico e modular e orientado a objetos).
Moodle também é um verbo que descreve o ato de navegar preguiçosamente por algum lugar,
fazendo coisas à medida que vão lhe aparecendo, de uma forma agradável que geralmente leva
a criatividade e aprendizado.

O Moodle foi criado por Martin Dougiamas, um cientista da computação e educador que empregou algum tempo
dando suporte ao AVEA de uma universidade em Perth, na Austrália. Ele foi ficando frustrado com o sistema
e percebeu que ele tinha sido criado por engenheiros e não por educadores. Marting então percebeu que um sistema
criado por alguém que começou pensando no processo educacional, ao invés de no processo de engenharia,
seria infinitamente melhor do que aquele sistema com o qual ele precisava trabalhar.
Com isso, ele colocou seus diplomas de pós-graduação em Educação e Ciência da Computação para trabalhar e começou a 
desenvolver o Moodle como uma alternativa. Atualmente, Martin trabalha em tempo integral com o Moodle.
Uma comunidade de desenvolvedores de software livre dedicados ao redor do mundo trabalha com ele num esforço coletivo
de tornar o Moodle o melhor AVEA disponível. Marting vive na Austrália com sua esposa, filha e filho.

## A quem este livro é destinado

Este livro é para pessoas que querem ministrar um curso utilizando o Moodle. Você pode utilizar o Moodle para ministrar um curso totalmente online ou para complementar um curso presencial. Não importa se você vai ensinar no ensino fundamental, no ensino superior ou na educação corporativa; você pode utilizar as ferramentas disponíveis no Moodle para criar uma classe efetiva.

## Pré-requisitos: o que você precisa antes de começar

Para utilizar este livro, você vai precisar do seguinte:

Ter acesso a um Moodle instalado e configurado em um servidor, como professor em um curso ou como administrador.

OU

Você pode baixar e instalar o Moodle no seu computador pessoal (ou pedir para que alguém faça isso para você). Você pode fazer o download da versão mais atual do Moodle em https://download.moodle.org/releases/latest/ e então instalá-lo utilizando as seguintes instruções disponíveis em https://docs.moodle.org/en/Installing_Moodle:

Também é possível fazer o download Moodle do utilizando o software de controle de versão git, conforme https://docs.moodle.org/en/Git_for_Administrators

Para utilizar as versões recentes do Moodle é recomendado utilizar um navegador atualizado.
Abaixo você pode ver a lista de navegadores e a versão mínima para utilziar o Moodle

|Navegador                  |Versão mínima|Versão recomendada|Observações|
|---------------------------|-------------|------------------|-----------|
|Google Chrome              |30.0         |Última            ||
|Mozilla Firefox            |25.0         |Última            ||
|Apple Safari               |6            |Última            ||
|Microsoft Internet Explorer|9            |Última            |Versão 10 é necessária para fazer upload ao arrastar-e-soltar conteúdo de fora do navegador para o Moodle|

Fonte: https://docs.moodle.org/dev/Moodle_2.7_release_notes#Client_requirements

## Como utilizar este livro

Este livro foi escrito para instrutores aprendendo a utilizar o Moodle.  No entanto, ele não é apenas um manual "passo-a-passo".
Seu curso não será melhor apenas por utilizar o Moodle. Apenas aplicando técnicas educacionais efetivas é que você poderá
conhecer e utilizar todo o potencial do Moodle.

A interface do Moodle pode ser altamente personalizada. As descrições e "screenshots" neste livro ilustram a interface padrão,
sem nenhuma personalização. Se você mudou a ordem dos blocos no seu curso ou se o administrador do sistema mudou
a aparência da interface principal, seu sistema será um pouco diferente do mostrado nos "screenshots" deste livro.

O capítulo 1 discute o que os Ambientes Virtuais de Ensino Aprendizagem têm a oferecer e quais as características do Moodle o tornam especial para a educação à distância.

O capítulo 2 junta todas as diferentes ferramentas em um conjunto e mostra algumas maneiras criativas em que professores podem utilizar o Moodle.

O capítulo 3 nos inicia no uso do Moodle. Nós vamos criar uma conta, revisar a interface básica, nos acustumar com algumas convenções e iniciar um curso.

O capítulo 4 mostra como adicionar conteúdos estáticos (chamados pelo Moodle de "recursos") no seu curso.

O capítulo 5 megulha no ambiente de ensino aprendizado, para entender a utilização dos papéis, organizar alunos em grupos e como obter relatórios de atividade dos estudantes.

O capítulo 6 nos familiariza com os editores de texto presentes no Moodle.

Os capítulos 7 a 18 tratam individualmente das ferramentas disponível no pacote padrão do Moodle. We’ll discuss how and when to use forums, hold chat sessions, send messages, give quizzes, set assignments, develop shared glossaries and databases, create pathed lessons, collaboratively develop web pages, create blogs, set up surveys and polls, and record student grades. Each chapter covers how to add the tool to your course, discusses the options available, and gives you some creative ideas for effectively using the tool in your class.

O capítulo 19 mostra como administrar um site Moodle. Geralmente essas funções são executadas por um administrador de sistemas, mas se você está sozinho nesta jornada, existe muito poder atrás das cortinas.

Você pode utilizar este livro de pelo menos duas formas diferentes. First, you can read it cover to cover. Hopefully, you’ll find it so compelling that you won’t be able to put it down until you’ve finished it. Or you can use it like a reference manual. The beginning of each tool chapter covers the how-to’s and the options. If you get lost, flip to the appropriate chapter and take it from the beginning.

### **Happy Moodling!!!** ###

Convenções utilizadas neste livro

As seguinte convenções tipográficas são utilizadas neste livro:

- *Itálico*
: Indica novos termos, URLs, endereços de e-mail, nomes de arquivos e extensões de arquivos.

- Largura fixa
: Utilizado para exemplos de código, e em parágrafos para termos referentes a elementos de programas como variáveis, nomes de funções, bases de dados, tipos de dados, variávels de ambiente, declaraçẽs e palavras-chave.

- ![](images/tip-icon.jpg)
: Utilizado para dicas, sugestões e considerações em geral.

## Agradecimentos do autor da edição original em inglês

*Jaswinder Singh*: Sou grato a Jason Cole e Helen Foster por escreverem o livro "Using Moodle". O trabalho neste livro foi baseado no livro "Using Moodle 2nd Edition" e na documentação do Moodle. Eu sou grato também a toda a comunidade Moodle por ter criado um AVEA tão agradável, que é tão popular, e especialmente ao Martin Dogiamas por tê-lo criado. Este livro é trabalho de toda a comunidade Moodle que escreveu a documentação durante todos estes anos.

Eu sou grato também ao Mr. Jai Gupta da Vidya Mantra EduSystems Pvt. Ltd. e ao Mr. Vikram Solia da Ballistic Learning por me apresentarem o Moodle e me encorajar a escrever este livro.

Esta é minha tentativa de retribuir à comunidade minha pequena parte.
