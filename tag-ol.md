# TAG `<ol>`

<br>

> **Documentação**: [clique aqui](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/ol)

<br>

### Detalhes

* `<ol>` = lista ordenada (ordered list), ou seja, os elementos são numerados/indice.
* Para mudar esses sinais, basta adicionar a propriedade `list-style-type` no CSS.

### Atributos

*  `compact` = descontinuada
 
*  `type` = indica o tipo de numeração
    * `type="a"` = indica letras minúsculas
    * `type="A"` = indica letras maiúsculas
    * `type="i"` = indica algarismos romanos minúsculos
    * `type="I"` = indica algarismos romanos maiúsculos
    * `type="1"` = indica números (por padrão)
  
* `start` = atributo inteiro que especifica o valor inicial da numeração dos elementos da lista (Exemplo: [clique aqui](#exemplo-usando-start))

* `reversed` = atributo booleano que inverte a numeração dos elementos da lista (Exemplo: [clique aqui](#exemplo-usando-reversed))

### Exemplo

* Código
  
  ```html
  <ol>
    <li>primeiro item</li>
    <li>segundo item</li>
    <li>terceiro item</li>
  </ol>
  ```

* Demonstração

  <ol>
    <li>primeiro item</li>
    <li>segundo item</li>
    <li>terceiro item</li>
  </ol>
  
### Exemplo usando `start`

* Código
  
  ```html
  <ol start="7">
    <li>primeiro item</li>
    <li>segundo item</li>
    <li>terceiro item</li>
  </ol>
  ```

* Demonstração

  <ol start="7">
    <li>primeiro item</li>
    <li>segundo item</li>
    <li>terceiro item</li>
  </ol>
  
### Exemplo usando `reversed`

* Código
  
  ```html
  <ol reversed>
    <li>primeiro item</li>
    <li>segundo item</li>
    <li>terceiro item</li>
  </ol>
  ```

* Demonstração

  <ol reversed>
    <li>primeiro item</li>
    <li>segundo item</li>
    <li>terceiro item</li>
  </ol>
