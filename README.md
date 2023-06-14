# Projeto Galeria de Imagens 🖼

Este foi na verdade uma pequena prática para aprender e desenvolver novas habilidades de HTML e CSS juntamente com a [Rocketseat](https://app.rocketseat.com.br/dashboard).

Aqui pude ver mais sobre CSS Grid, alguns novos atributos como o "loading" que faz com que a imagem vai carregando a medida que rolamos a página. Também foi vista a propriedade
"aspect-ratio" que define a proporção do tamanho da imagem.

### O atributo 'loading'
```

<img loading="lazy" src="https://source.unsplash.com/random?a=1" alt="Abstract Name 1">

```

### A propriedade 'aspect-ratio'
```

.model-1 .container:nth-child(1) img,
.model-2 .container:nth-child(3) img {
    aspect-ratio: 9/16;
}

.horizontal img {
    aspect-ratio: 16/9;
}

```

Veja abaixo uma imagem de como fica a galeria de imagens.
<img src="./src/design/imagens-do-projeto.PNG">

Abaixo você pode conferir como ficou o resultado final da galeria de imagens.
<img src="./src/design/projeto-gallery-images.gif">

## Tecnologias utilizadas
- HTML
- CSS
