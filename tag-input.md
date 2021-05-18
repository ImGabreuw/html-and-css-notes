# TAG `<input>`

<br>

> **Documentação**: [clique aqui](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/input)

<br>

### Detalhes

* `<input>` = é responsável pela coleta de dados em um formulário, pois nela é onde o usuário irá inserir suas informações.
* A semântica e estética de um `<input>` varia de acordo com o atribuito `type`.

---

### Atributos

*  `type` = por padrão, o tipo de um `<input>` é `text` (**[Clique aqui](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/input) para ver outros valores possíveis**)
 
*  `accept` = apenas para `<input>` do `type="file"`
    * `accept=".jpg,.png,.doc"` = uma (ou +) extensão/ões de arquivo começando com o caractere STOP (U+002E)
    * `accept="image/*"` = um tipo MIME válido sem extensões (`audio/*` / `video/*` / `image/*`)

*  `autocomplete ` = navegador completará o campo automaticamente
    * `autocomplete="off"` = navegador não irá auxiliar o usuário no preenchimento desse campo
    * `autocomplete="on"` = padrão

* `checked` = apenas para `<input>` do `type="radio"` ou `type="checkbox"`
    * `<input type="radio" checked />` = `<input>`, por padrão, virá marcado (checado)

* `disabled`
    * `<input disabled />` = usuário não poderá interagir com o `<input>`

* `value` = valor inicial do `<input>` 
    * é obrigatório apenas no `<input type="radio">` e `<input type="checkbox">`
   
* `required` = usuário é obrigado a inserir um valor válido no `<input>` para que o formulário seja enviado

* `readonly` 
    * `<input readonly />` = usuário não poderá modificar o valor do `<input>`
    * esse atributo é ignorado para os seguintes tipos de `<input>`: `hidden`, `range`, `color`, `checkbox`, `radio`, `file` e botões

---

### Exemplo com `action="GET"`

* Código
  
  ```html
  <form action="#" method="GET">
    <label for="GET-name">Nome:</label>
    <input id="GET-name" type="text" name="name">
    <button type="submit">Enviar</button>
  </form>
  ```

* Demonstração

  <form action="#" method="GET">
    <label for="GET-name">Nome:</label>
    <input id="GET-name" type="text" name="name">
    <button type="submit">Enviar</button>
  </form>
  
### Exemplo com `action="POST"`

* Código
  

* Demonstração
