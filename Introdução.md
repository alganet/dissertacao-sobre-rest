# Introdução

*Com licença... você disse 'facas'?*
        -- City Gent #1 (Michael Palin), The Architects Sketch [111]

Assim como previsto anteriormente por Perry e Wolf [105], a arquitetura de software tem sido um ponto de foco
para pesquisas de engenharia de software nos anos 1990.A complexidade dos sistemas de software modernos implicaram em
uma ênfase ainda maior em sistemas separados por componentes, onde a implementação é particionada em componentes independentes
que se comunicam para realizar as tarefas desejadas. A pesquisa científica de arquitetura de software investiga métodos para
determinar qual a melhor maneira de particionar um sistema, como identificar seus componentes e estabelecer ua comunicação
entre eles, como a informação é estabelecida, como os elementos do sistema podem evoluir independentemente e como tudo isso
pode ser descrito utilizando-se de uma notação formal e informal.

Uma boa arquitetura não é criado no vácuo. Todas as decisões de *design* em um nível arquitetônico deveria ser feito dentro de
um contexto de requerimentos funcionais, comportamentais e sociais do sistema sendo criado, que é um princípio que se aplica
tanto para a arquitetura de software quanto para arquitetura do ramo de construção tradicional. A diretrize que indica que
"[a forma segue a função](https://pt.wikipedia.org/wiki/Forma_segue_a_fun%C3%A7%C3%A3o)" vem de centenas de anos de exeperiência
com projetos de construção que falharam e são frequentemente ignorados por particantes de software. A parte engraçada do esboço de
[Monty Python](https://pt.wikipedia.org/wiki/Monty_Python), citado acima, é uma noção absurda que um arquiteto, ao ser
confrontado com o objetivo de projetar um bloco urbano de apartamentos, apresentaria um *design* de construção com todos os componentes
de um frigorífico moderno. Pode até ser o melhor *design* do melhor frigorífico á concebido, mas seria de pouquíssimo conforto para
os inquilidos assim que fossem levados para os corredores contendo facas rotativas.

A hipérbole do [O Esboço dos Arquitetos](http://www.montypython.net/scripts/architec.php) (do grupo [Monty Python](http://www.montypython.net/))
pode parecer ridícula, mas considere o quão frequentemente vemos projetos sendo começados com a adoção da última moda em *design* arquitetônico
e somente mais tarde descobrem se o tipo de arquitetura adotada atende os requerimentos. *Design-por-burbúrio (Design-by-buzzword)* é uma ocorrência bem comum.
Pelo menos algum deste comportamento adotado dentro da indústria de software é devido a falta de compreensão do motivo de um conjunto de restrições
é útil. Em outras palavras, a razoabilidade por trás de boas arquiteturas de software não são aparentes para projetistas quando estas arquiteturas são
selecionados para reutilização.

Esta dissertação explora uma junção nas fronteiras da investigação em duas disciplinas da ciência da computação: *software* e *networking*.
Pesquisas de software tem se interessado, por muito tempo, pela categorização de projetos de software - *design* - e o desenvolvimento
de metodologias de *design*, mas raramente tem conseguido avaliar objetivamente o impacto dos vários tipos de *design* no comportamento
de um sistema. A pesquisa na área de *networking*, por outro lado, está focada nos detalhes da comunicação genérica entre sistemas e na
melhoria do desempenho de técnicas de comunicação específicas, frequentemente ignorando o fato de que ao mudar a forma de como os estilos de interações
acontecem em uma aplicação pode ter mais impacto na performance do que os protocolos de comunicação utilizados para estas mesmas interações.
Meu trabalho é motivado pelo desejo de compreender e avaliar o estilo de arquitetura de aplicações de software baseadas em redes através do uso de
princípios de restrições arquitetônicas, obtendo, assim, a funcionalidades, desempenho e propriedades sociais *(comunicação entre elementos)* desejadas de uma arquitetura.
Quando um nome e um conjunto coordenado de restrições arquitetônicas se torna um estilo arquitetônico.