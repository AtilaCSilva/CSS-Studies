# A Cascata (cascading)

A escolha do browser de qual regra aplicar, caso haja muitas regras para o mesmo elemento.

*Seu estilo é lido de cima para baixo,

E levado em consideração 3 fatores

1. Origem do estilo 
2. Especifidade
3. Importância

### Origem do estilo
inline > tag style > tag link

### Epecifidade

É um cálculo matematico, onde, cada tipo de seletor e origem do estilo, possuem valores a serem considerados.

0.Universal selector, cobinators e negation pseudo-class (:not())
1. Element type selector, e pseudo-elements (::before, ::after)
10.classses e attribute selectors ("type="radio"))
100. ID selector
1000. Inline

### A regra !important

*cuidado, evite os uso
* não é considerado uma boa prática
* quebra o fluxo natural da cascata

