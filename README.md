# Diretivas
 A ideia por trás das diretivas é tornar manipuláveis os objetos do DOM (document object model)

 ### Tipos de Diretivas
 - `De atributos:` promovem mudanças em objetos já existentes
 - `Estruturais:` acrescentam ou removem objetos do DOM 


### As diretivas
> - [`NgStyle`](https://github.com/jcarloscody/angular_diretivas/tree/master/src/app/ng-style)  **`[ngStyle]="{propriedade: variavel}"`** Você conseguirá definir em tempo de execução o estilo de um objeto do DOM. 
> - [`NgClass`](https://github.com/jcarloscody/angular_diretivas/tree/master/src/app/ng-class)  **`[ngClass]="variavel"`** Você conseguirá definir/modificar classes para um objeto do DOM. 
> - [`NgIf`](https://github.com/jcarloscody/angular_diretivas/tree/master/src/app/ng-if)  **`*ngIf="variavelBoleana ou expressão lógica"`** Com determinada expressão lógica conseguimos habilitar ou não determinado componente do html. 
> - [`NgFor`](https://github.com/jcarloscody/angular_diretivas/tree/master/src/app/ng-for)  **`*ngFor="let item of items"`** Criamos vários elementos a partir de um loop.
>   - **`*ngFor="let item of items; let i=index"`**
> - [`NgSwitch`](https://github.com/jcarloscody/angular_diretivas/tree/master/src/app/ng-switch )  **`*[ngSwitch]="variavel"  |   *ngSwitchCase="'value'"`** Possui a mesma ideia do switch/case.
>  - observe que é "''" isto porque se deixarmos apenas assim "" ele procurará uma variável.
> - [`NgTemplate`](https://github.com/jcarloscody/angular_diretivas/tree/master/src/app/ng-template)  **`<ng-template #variave_de_referencia> </ng-template>`** Uma diretiva para renderizar página html, mas usando um component você consegue condicionar por exemplo a renderização.
> - [`NgContainer`](https://github.com/jcarloscody/angular_diretivas/tree/master/src/app/ng-container)  **`<ng-container> </ng-container>`** O container chegou numa hora para ajudar na implementação de um algoritmo que precisa usar concomitantemente o loop + condição, o ngFor + ngIf, para isso usamos o .