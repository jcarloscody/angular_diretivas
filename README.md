# Diretivas
 A ideia por trás das diretivas é tornar manipuláveis os objetos do DOM (document object model)

 ### Tipos de Diretivas
 - `De atributos:` promovem mudanças em objetos já existentes
 - `Estruturais:` acrescentam ou removem objetos do DOM 


### As diretivas
> - [`NgStyle`](https://github.com/jcarloscody/angular_diretivas/tree/master/src/app/ng-style)  **`[ngStyle]="{propriedade: variavel}"`** Você conseguirá definir em tempo de execução o estilo de um objeto do DOM. 
> - [`NgClass`](https://github.com/jcarloscody/angular_diretivas/tree/master/src/app/ng-class)  **`[ngClass]="variavel"`** Você conseguirá definir/modificar classes para um objeto do DOM. 
> - [`NgIf`](https://github.com/jcarloscody/angular_diretivas/tree/master/src/app/ng-if)  **`*ngIf="variavelBoleana ou expressão lógica"`** Com determinada expressão lógica conseguimos habilitar ou não determinado componente do html. 
> - [`NgFor`](https://github.com/jcarloscody/angular_diretivas/tree/master/src/app/ng-for)  **`*ngIf="variavelBoleana ou expressão lógica"`** Criamos vários elementos a partir de um loop.