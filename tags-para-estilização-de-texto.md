# TAGs para estilizar textos

### TAGs: `<strong>` e `<b>` 

* Ambos deixam o texto/palavra em negrito.

* `<strong>`
  
  * Mais semântica em relação à `<b>`.
  * É um estado lógico, ou seja, além de mudar o estilo do texto, o leitor de tela, quando for ler o coteúdo dessa TAG, ele irá ler com entonação mais forte.
  
  * Código
   
    ```html
    <p>Lorem <strong>ipsum dolor</strong> sit amet consectetur, adipisicing elit. Dolorum, labore.</p>
    ```
    
  * Demonstração
    
    <p>Lorem <strong>ipsum dolor</strong> sit amet consectetur, adipisicing elit. Dolorum, labore.</p>
    
 * `<b>`
  
  * É um estado físico, ou seja, muda apenas a aparência do texto.
  
  * Código
   
    ```html
    <p>Lorem <b>ipsum dolor</b> sit amet consectetur, adipisicing elit. Dolorum, labore.</p>
    ```
    
  * Demonstração
    
    <p>Lorem <b>ipsum dolor</b> sit amet consectetur, adipisicing elit. Dolorum, labore.</p>
    
<br>
    
> Para mais informações sobre a diferença entre as TAGs `<b>` e `<strong>`, basta [clicar aqui](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/strong)
 
---
    
### TAGs: `em` e `i`

* `<em>`
  
  * Além de mudar o estilo da letra para itálico, quando o leitor de tela for ler o conteúdo da TAG, ele irá ler com mais intensidade (dando relevância a esse trecho) 
  
  * Código
   
    ```html
    <p>Lorem <em>ipsum dolor</em> sit amet consectetur, adipisicing elit. Dolorum, labore.</p>
    ```
    
  * Demonstração
    
    <p>Lorem <em>ipsum dolor</em> sit amet consectetur, adipisicing elit. Dolorum, labore.</p>
    
* `<i>`
  
  * Muda apenas o estilo da letra para itálico
  
  * Código
   
    ```html
    <p>Lorem <i>ipsum dolor</i> sit amet consectetur, adipisicing elit. Dolorum, labore.</p>
    ```
    
  * Demonstração
    
    <p>Lorem <i>ipsum dolor</i> sit amet consectetur, adipisicing elit. Dolorum, labore.</p>
