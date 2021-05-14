# TAG `<form>`

<br>

> **Documentação**: [clique aqui](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/form)

<br>

### Detalhes

* `<form>` = enviar informações do usuário para o back-end do site
* É possível utilizar as pseudo-classes do CSS `:valid` e `:invalid` para aplicar estilo à TAG `<form>`

---

### Atributos

*  `action` = url para onde as informações do formulário serão enviados
 
*  `autocomplete` = navegador completará alguns campos do formulário (email/senha/etc) automaticamente
    * `autocomplete="off"` = navegador não irá auxiliar o usuário no preenchimento do formulário
    * `autocomplete="on"` = padrão

*  `method` = indicação do método HTTP na hora do envio dos dados
    * `method="POST"` = execução do [método POST](https://www.w3.org/Protocols/rfc2616/rfc2616-sec9.html#sec9.5)
    * `method="GET"` = execução do [método GET](https://www.w3.org/Protocols/rfc2616/rfc2616-sec9.html#sec9.3)

* `novalidate` = no envio, o navegador não irá fazer uma validação prévia (varia de navegador para navegador) dos dados do formulário

* `target` = meio para mostrar a resposta do envio
    * `target="_self"` = página será recarregada
    * `target="_blank"` = abrir em um novo guia

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
  
  ```html
  <form action="#" method="POST">
    <label for="POST-name">Nome:</label>
    <input id="POST-name" type="text" name="name">
    <button type="submit">Salvar</button>
  </form>
  ```

* Demonstração

  <form action="#" method="POST">
    <label for="POST-name">Nome:</label>
    <input id="POST-name" type="text" name="name">
    <button type="submit">Salvar</button>
  </form>
  
### Exemplo com `<fieldset>` e `<legend>`

* Código
  
  ```html
  <form action="#" method="POST">
    <fieldset>
      <legend>Título</legend>
      <input type="radio" name="radio" id="radio"> <label for="radio">Clique aqui</label>
    </fieldset>
  </form>
  ```

* Demonstração
 
  <form action="#" method="POST">
    <fieldset>
      <legend>Título</legend>
      <input type="radio" name="radio" id="radio"> <label for="radio">Clique aqui</label>
    </fieldset>
  </form>
