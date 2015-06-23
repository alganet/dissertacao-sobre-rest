Estilos de Arquitetura e o Projeto de Arquiteturas de Software Baseadas em Redes
====================

---

TÃ­tulo original: [Architectural Styles and the Design of Network-based Software Architectures](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm).

Fielding, Roy Thomas. [Architectural Styles and the Design of Network-based Software Architectures](https://www.ics.uci.edu/~fielding/pubs/dissertation/faq.htm). Doctoral dissertation, University of California, Irvine, 2000.

TraduÃ§Ã£o nÃ£o oficial e comentÃ¡rios por [Alexandre Gaigalas](http://gaigalas.net). 

Leia sobre as [permissÃµes de uso da obra](https://www.ics.uci.edu/~fielding/pubs/dissertation/faq.htm) (em inglÃªs).

---

#### [UNIVERSIDADE DA CALIFÃ“RNIA, IRVINE](https://pt.wikipedia.org/wiki/Universidade_da_Calif%C3%B3rnia)
### Estilos de Arquitetura e o Projeto de Arquiteturas de Software Baseadas em Redes

#### DISSERTAÃ‡ÃƒO

enviada para satisfaÃ§Ã£o parcial dos requerimentos para graduaÃ§Ã£o como

#### DOUTOR DE FILOSOFIA

em InformaÃ§Ã£o e CiÃªncias da ComputaÃ§Ã£o

por

[Roy Thomas Fielding](https://www.ics.uci.edu/~fielding/)

2000



ComitÃª de DissertaÃ§Ã£o:<br>
Professor [Richard N. Taylor](http://www.ics.uci.edu/~taylor/), Chair<br>
Professor [Mark S. Ackerman](https://www.eecs.umich.edu/eecs/faculty/eecsfaculty.html?uniqname=ackerm)<br>
Professor [David S. Rosenblum](http://www.comp.nus.edu.sg/~david/)<br>

---

## DedicatÃ³ria

Aos<br>
meus pais,<br>
[Pete](http://www.faculty.uci.edu/profile.cfm?faculty_id=2352) e Kathleen Fielding,<br>
que fizeram tudo isso possÃ­vel,<br>
por seu infindÃ¡vel encorajamento e paciÃªncia.<br>

E tambÃ©m para<br>

[Tim Berners-Lee](https://pt.wikipedia.org/wiki/Tim_Berners-Lee),<br>

por fazer a _World Wide Web_ um projeto aberto e colaborativo.


> O que Ã© vida?<br>
> Ã‰ o piscar de um vagalume na noite.<br>
> Ã‰ o respirar de um bÃºfalo no inverno.<br>
> Ã‰ a pequena sombra que corre junto Ã  grama.<br>
> e se perde no nascer do sol.<br>
> **Ãšltimas palavras de Crowfoot (1890), guerreiro Blackfoot e orador.**

---

*ComentÃ¡rios do tradutor*:

Richard descreve a si mesmo [em sua pÃ¡gina pessoal](https://www.ics.uci.edu/~fielding/) como uma mistura de [Maori](https://en.wikipedia.org/wiki/M%C4%81ori_people), [Kiwi](https://en.wikipedia.org/wiki/Kiwi_%28people%29), Ianque, IrlandÃªs, EscocÃªs, InglÃªs, e mendigo das praias da California. Ao citar [Crowfoot](https://en.wikipedia.org/wiki/Crowfoot), ele tambÃ©m faz uma referÃªncia Ã s [Primeiras NaÃ§Ãµes](https://pt.wikipedia.org/wiki/Primeiras_Na%C3%A7%C3%B5es).

---

&nbsp;

> Quase todo mundo se sente em paz com a natureza: ouvindo as ondas do oceano<br>
> contra a praia, em um calmo lago, em um campo gramado, em uma charneca ventanosa.<br>
> Um dia, quando tivermos aprendido o jeito atemporal [de fazer as coisas], nÃ³s sentiremos o mesmo<br>
> para com as nossas cidades, e nÃ³s sentiremos a mesma paz nelas, tal como sentimos hoje caminhando pelo<br>
> oceano, ou deitados na vasta grama de um pasto.<br>
> **Cristopher Alexander, The Timeless Way of Building (1979)**

---

*ComentÃ¡rios do tradutor*:

[Cristopher Alexander](https://pt.wikipedia.org/wiki/Christopher_Alexander) foi um arquiteto que inspirou muitas outras Ã¡reas com uma obra chamada [The Timeless Way of Building](https://en.wikipedia.org/wiki/The_Timeless_Way_of_Building). Essa obra tambÃ©m Ã© citada, por exemplo, no famoso [PadrÃµes de Projeto](https://en.wikipedia.org/wiki/Design_Patterns).

---