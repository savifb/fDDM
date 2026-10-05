# Estrutura SCSS

Conversão do `Código colado.css` para uma estrutura modular SCSS, mantendo os seletores e regras visuais do CSS original.

## Estrutura

```text
scss_estrutura/
├── main.scss
├── abstracts/
│   └── _variables.scss
├── base/
│   ├── _reset.scss
│   └── _utilities.scss
├── components/
│   ├── _brand.scss
│   ├── _buttons.scss
│   └── _navbar.scss
├── layout/
│   ├── _footer.scss
│   └── _site.scss
└── sections/
    ├── _about.scss
    ├── _contact.scss
    ├── _hero.scss
    ├── _services.scss
    └── _testimonials.scss
```

## Compilação

Com Dart Sass:

```bash
sass main.scss estilo.css
```

Ou em modo watch:

```bash
sass --watch main.scss:estilo.css
```

`main.scss` é o ponto de entrada. Os arquivos iniciados por `_` são partials e são incorporados pelo `@use`.

## Observação

Nesta primeira organização, o comportamento visual e os nomes das classes foram preservados. A separação é por responsabilidade: tokens, base, layout, componentes e seções.
