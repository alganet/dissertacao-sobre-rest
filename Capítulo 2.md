# CAPÍTULO 2

## Arquiteturas de Aplicativos Baseados em Rede

Este capítulo continua a discussão de material de apoio concentrando-se em arquiteturas de aplicativos baseados em rede e descrevendo como os estilos podem ser usados ​​para guiar o *design* arquitetônico.


### 2.1 Escopo

A arquitetura é encontrada em vários níveis dentro de sistemas de software. Esta dissertação analisa o nível mais alto de abstração em arquitetura de software, onde as interações entre componentes são capazes de ser realizadas em comunicação de rede. Nós limitamos a nossa discussão a estilos de arquiteturas de aplicativos baseados em rede, a fim de reduzir as dimensões de variação entre os estilos estudados.

### 2.1.1 Baseada em Rede vs. Distribuída

A distinção primária entre as arquiteturas baseadas em rede e arquiteturas de software em geral é que a comunicação entre os componentes é restrita a passagem de mensagens [[6](Referências.md#6)], ou o equivalente a passagem de mensagens se um mecanismo mais eficiente pode ser selecionado no tempo de execução com base na localização de componentes [[128](Referências.md#128)].

**Tanenbaum e van Renesse** [[127](Referências.md#127)] fazem uma distinção entre sistemas distribuídos e sistemas baseados em rede: um sistema distribuído é aquele que olha para seus usuários como um sistema centralizado comum, mas é executado em várias CPUs independentes. Em contraste, os sistemas baseados em rede são os que são capazes de operação através de uma rede, mas não necessariamente de uma forma que é transparente para o utilizador. Em alguns casos, é desejável que o usuário esteja consciente da diferença entre uma ação que requer um pedido de rede e um que pode ser satisfeita no seu sistema local, especialmente quando a utilização da rede implica um custo extra de transacção [[133](Referências.md#133)]. Esta dissertação abrange os sistemas baseados em rede ao não limitar os estilos candidatos àqueles que preservam transparência para o usuário.

