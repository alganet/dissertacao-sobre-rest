Estilos de Arquitetura e o Projeto de Arquiteturas de Software Baseadas em Redes
====================


Título original: [Architectural Styles and the Design of Network-based Software Architectures](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm).

Fielding, Roy Thomas. [Architectural Styles and the Design of Network-based Software Architectures](https://www.ics.uci.edu/~fielding/pubs/dissertation/faq.htm). Doctoral dissertation, University of California, Irvine, 2000.

Tradução não oficial e comentários por [Alexandre Gaigalas](http://gaigalas.net). 

Leia sobre as [permissões de uso da obra](https://www.ics.uci.edu/~fielding/pubs/dissertation/faq.htm) (em inglês).

---

#### [UNIVERSIDADE DA CALIFÓRNIA, IRVINE](https://pt.wikipedia.org/wiki/Universidade_da_Calif%C3%B3rnia)
### Estilos de Arquitetura e o Projeto de Arquiteturas de Software Baseadas em Redes

#### DISSERTAÇÃO

enviada para satisfação parcial dos requerimentos para graduação como

#### DOUTOR DE FILOSOFIA

em Informação e Ciências da Computação

por

[Roy Thomas Fielding](https://www.ics.uci.edu/~fielding/)

2000


Comitê de Dissertação:<br>
Professor [Richard N. Taylor](http://www.ics.uci.edu/~taylor/), Chair<br>
Professor [Mark S. Ackerman](https://www.eecs.umich.edu/eecs/faculty/eecsfaculty.html?uniqname=ackerm)<br>
Professor [David S. Rosenblum](http://www.comp.nus.edu.sg/~david/)<br>

---

## Dedicatória

Aos<br>
meus pais,<br>
[Pete](http://www.faculty.uci.edu/profile.cfm?faculty_id=2352) e Kathleen Fielding,<br>
que fizeram tudo isso possível,<br>
por seu infindável encorajamento e paciência.<br>

E também para<br>

[Tim Berners-Lee](https://pt.wikipedia.org/wiki/Tim_Berners-Lee),<br>

por fazer a _World Wide Web_ um projeto aberto e colaborativo.


> O que é vida?<br>
> É o piscar de um vagalume na noite.<br>
> É o respirar de um búfalo no inverno.<br>
> É a pequena sombra que corre junto à grama.<br>
> e se perde no nascer do sol.<br>
> **Últimas palavras de Crowfoot (1890), guerreiro Blackfoot e orador.**

---

*Comentários do tradutor*:

Richard descreve a si mesmo [em sua página pessoal](https://www.ics.uci.edu/~fielding/) como uma mistura de [Maori](https://en.wikipedia.org/wiki/M%C4%81ori_people), [Kiwi](https://en.wikipedia.org/wiki/Kiwi_%28people%29), Ianque, Irlandês, Escocês, Inglês, e mendigo das praias da California. Ao citar [Crowfoot](https://en.wikipedia.org/wiki/Crowfoot), ele também faz uma referência às [Primeiras Nações](https://pt.wikipedia.org/wiki/Primeiras_Na%C3%A7%C3%B5es).

---

&nbsp;

> Quase todo mundo se sente em paz com a natureza: ouvindo as ondas do oceano
> contra a praia, em um calmo lago, em um campo gramado, em uma charneca ventanosa.<br>
> Um dia, quando tivermos aprendido o jeito atemporal [de fazer as coisas], nós sentiremos o mesmo
> para com as nossas cidades, e nós sentiremos a mesma paz nelas, tal como sentimos hoje caminhando pelo
> oceano, ou deitados na vasta grama de um pasto.
> **Cristopher Alexander, The Timeless Way of Building (1979)**

---

*Comentários do tradutor*:

[Cristopher Alexander](https://pt.wikipedia.org/wiki/Christopher_Alexander) foi um arquiteto que inspirou muitas outras áreas com uma obra chamada [The Timeless Way of Building](https://en.wikipedia.org/wiki/The_Timeless_Way_of_Building). Essa obra também é citada, por exemplo, no famoso [Padrões de Projeto](https://en.wikipedia.org/wiki/Design_Patterns).

---