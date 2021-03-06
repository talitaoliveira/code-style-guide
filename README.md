# Code Style Guide

1. [Sintaxe](#sintaxe)
1. [Declaração](#declarações)
1. [Comentários](#comentários)

### Sintaxe

Use sof-tabs com dois espaços:

```css
/* bom */
.btn {
  color: #fff;
}

/* ruim */
.btn {
	color: #fff;
}
```

Use sempre aspas duplas:

```css
/* bom */
.btn {
  background-image: url("imagem.jpg");
  font-family: "Helvetica Neue", sans-serif;
}

/* ruim */
.btn {
  background-image: url('imagem.jpg');
  font-family: 'Helvetica Neue', sans-serif;
}
```

Inclua um espaço antes de abrir as chaves da regra:

```css
/* bom */
.btn {
  color: #fff;
}

/* ruim */
.btn{
  color: #fff;
}
```

Feche as chaves em uma nova linha:

```css
/* bom */
.btn {
  color: #fff;
}

/* ruim */
.btn {
  color: #fff;}
```

Inclua um espaço depois do : da declaração:

```css
/* bom */
.btn {
  color: #fff;
}

/* ruim */
.btn {
  color:#fff;
}
```

Sempre use um ; no fim da declaração:

```css
/* bom */
.btn {
  color: #fff;
}

/* ruim */
.btn {
  color: #fff
}
```

Mantenha sempre uma declaração por linha:

```css
/* bom */
.nav,
.footer,
.btn {
  color: #fff;
}

/* ruim */
.nav, .footer, .btn {
  color: #fff;
}
```

Sempre separe as regras por uma linha em branco:

```css
/* bom */
.btn {
  color: #fff;
}

.nav-item {
  color: #fff; 
}

/* ruim */
.btn {
  color: #fff
}
.nav-item {
  color: #fff; 
}
```

Sempre use caixa baixa:
```css
/* bom */
.nav-item {
  color: #fff; 
}
/* ruim */
.Nav-item {
  color: #fff; 
}
```

Sempre use hífens para separar os nomes:
```css
/* bom */
.nav-item {
  color: #fff; 
}
/* ruim */
.nav_item {
  color: #fff; 
}
```

Sempre que usar valores hexadecimais usar reduzidos:
```css
/* bom */
.nav-item {
  color: #fff; 
}
/* ruim */
.nav-item {
  color: #ffffff; 
}
```

Não especifique unidades quando o valor for igual a zero:
```css
/* bom */
.nav-item {
  padding: 0;
}
/* ruim */
.nav-item {
  padding: 0px;
}
```

Não use valores iniciados com zero:
```css
/* bom */
.nav-item {
  transition: color .3s;
}
/* ruim */
.nav-item {
  transition: color 0.3s;
}
```

### Declarações
Todas as declarações devem estar em ordem alfabetica.

```css
/* bom */
.btn {
  background: #000;
  color: #fff;
  display: inline-block;
  margin: 0;
  padding: 10px;
}
/* ruim */
.btn {
  color: #FFF;
  background: #000;
  margin: 0;
  padding: 10px;
  display: inline-block;
}
```

### Comentários
```css
/* Bloco de comentário de seção
=============================================== */

/* Bloco de comentário de sub-seção
=================== */

/* Comentário Básico */
```