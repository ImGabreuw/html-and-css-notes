# Conceitos básicos sobre CSS

### Hierarquia

`id > class > TAG`

---

### `!important`

* Forçar o navegador a utilizar uma estilização, mesmo se estiver quebrando a hierarquia 

> OBS: Seu uso não é recomendado. Optar pelo uso de classes

---

### Estilo dentro do HTML

```html
<head>
  <style>
    /* Estilos */
  </style>
</head>
```

---

### Estilização por TAG

* Atribuir um estilo para um determinada TAG, porém de forma global

* **Exemplo**
  
  ```css
  h1 {
    background: red;
  }
  ```
  
  > Todos os h1 terão a cor vermelho

---
  
### Estilização por _class_

* Atribuir um estilo para todos os elementos que possuem uma certa classe
* Separar classes com nome composto por hífen (`azul-claro`)
* Nome de classe não pode ter acentos

<br>

* TAG com apenas 1 classe
  
  ```html
  <h1 class="azul">Título 1</h1>
  ```
  ```css
  .azul {
    background: blue;
  }
  ```
  
<br>
  
* TAG com apenas 2 ou + classe
  
  ```html
  <h1 class="azul sem-margem">Título 1</h1>
  ```
  ```css
  .azul {
    background: blue;
  }
  
  .sem-margem {
    margin: 0;
  }
  ```
  
---

### Estilização por Id

* Atribuir um estilo para um única TAG com o id correspondente
* O Id é **único**, ou seja, não pode ter elementos com o mesmo Id

> Utilizado apenas quando apenas um elememto possuir uma estilo único em toda a aplicação

* **Exemplo**
  
  ```html
  <h1 id="cabecalho-ola-mundo">Olá mundo</h1>
  ```
  ```css
  #cabecalho-ola-mundo {
    background: purple;
  } 
  ```
