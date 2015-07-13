Resumo da Dissertação
--------------

Modelos e Projetos de Arquiteturas de Software Baseadas em Redes

por

Roy Thomas Fielding

Doutor de Filosofia em Ciências da Informação

Universidade da Califórnia, Irvine 2000

Professor Richard N. Taylor, Chair


A Rede Mundial de Computadores *(World Wide Web)* foi bem-sucedida em grande parte porque a sua arquitetura de software foi desenvolvida de acordo com as necessidades de um sistema de hipermídia distribuído em larga escala. A *Web* foi desenvolvida iterativamente ao longo de dez anos através de uma série de modificações que resultaram nos padrões que definem a sua arquitetura atual. A fim de identificar os aspectos que foram necessários e as modificações indesejadas para a evolução da *Web*, um modelo para uma arquitetura *Web* moderna foi necessário para direcionar o desenvolvimento, a definição e a distribuição das aplicações.

A pesquisa científica de arquitetura de software investiga métodos para determinar qual a melhor maneira de particionar um sistema, como identificar seus componentes e estabelecer ua comunicação entre eles, como a informação é estabelecida, como os elementos do sistema podem evoluir independentemente e como tudo isso pode ser descrito utilizando-se de uma notação formal e informal. Meu trabalho é motivado pelo desejo de compreender e avaliar o estilo de arquitetura de aplicações de software baseadas em redes através do uso de princípios de restrições arquitetônicas, obtendo, assim, a funcionalidades, desempenho e propriedades sociais *(comunicação entre elementos)* desejadas de uma arquitetura. Um estilo de arquitetura é um conjunto coordenado de restrições arquitetônicas.

Esta dissertação define um *framework* para se compreender a arquitetura de software por meio de estilos de arquitetura e demonstra como estes estilos podem ser utilizados para direcionar o desenvolvimento arquitetônico de aplicações de software baseadas em rede. Uma pesquisa de estilos de arquitetura para aplicações baseadas em rede é utilizada para classificar estes estilos de acordo com as propriedades arquitetônicas que induzidas por eles para se obter uma arquitetura de hipermídia distribuída. Desta forma, eu introduzo o estilo de arquitetura da **Transferência de Representação de Estado *(Representation State Transfer - REST)*** e descrevo como o *REST* tem sido utilizado para direcionar o desenvolvimento da arquitetura da *Web* moderna.

*REST* enfatiza a escalabilidade de interações de componentes, generalização de interfaces, distribuição independente de componentes e intermediação  de componentes de forma a reduzir a latência de interação entre eles, reforço de segurança e o encapsulamento de sistemas legados. Eu descrebo os princípios de engenharia de software direcionados pelo *REST* e as restrições de interação escolhidas para respeitar estes princípios, comparando-os, em constrante, como as restrições de estilo de outras arquiteturas. Finalmente, eu descrevo as lições aprendidas da aplicação do *REST* aos padrões de **Protocolo de Transferência de Hipertexto *(Hypertext Transfer Protocol - HTTP)*** e **Identificador Uniforme de Recursos *(Uniform Resource Identifier - URI)*** e das subsequente distribuição de softwares em clientes e servidores *Web*. 