# Estrutura do HTML

### Estutura base

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <title>Título</title>
</head>
</html>
```

#### Emmet Abbreviation: `!` no arquivo .html + ENTER

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```

### TAGs

```html
<!-- TAG com corpo -->
<nomedatag> <!-- começo da TAG -->

  <!-- Corpo da TAG -->
  
  <nomedeoutratag>

    <!-- TAG sem corpo -->
    <tagsemcorpo />

    <!-- TAG com atributos -->  
    <tagsemcorpo atributo="valor"/> <!-- Pode ou não ter atributos que recebem valores -->
    <tagsemcorpo atributo="valor1 valor2"/> <!-- Atributos que podem receber 1 ou + valores -->

  </nomedeoutratag>

</nomedatag> <!-- fim da TAG -->
```

* Hierarquia de TAGs 
  * A indetação é uma forma de facilitar a visibilidade das TAGs filhas

* Podem ou não ter atributos
  * Existem atributos específicos para uma determinada TAG
  
* Geralmente, os atributos vem na abertura da TAG

### Arquivo com extensão `.html`

## OBS

* Os arquivos `.html` pode ser abertos/editados por qualquer ferramenta que entenda `.txt`
* HTML é case insensitive
* Site para validação do código HTML: [clique aqui](https://validator.w3.org/)
