# Exercício SASS — Módulo 13

Conversão do CSS do projeto de loja para SASS, utilizando variáveis e módulos.

## 📁 Estrutura de arquivos

```
sass/
├── abstracts/
│   ├── _variables.scss   → variáveis globais (cores, fontes, espaçamentos)
│   └── _mixins.scss      → mixins reutilizáveis (media queries, botões, flex)
├── base/
│   └── _reset.scss       → reset global de estilos
├── layout/
│   ├── _container.scss   → container e section
│   └── _header.scss      → cabeçalho e menu de navegação
├── components/
│   └── _products.scss    → grid de produtos e botão
└── styles.scss           → arquivo principal que importa todos os módulos
```

## ✅ Recursos SASS utilizados

- **Variáveis** (`$color-primary`, `$spacing-md`, etc.)
- **Módulos** (`@use` com alias)
- **Mixins** (`@mixin` e `@include`)
- **Nesting** (seletores aninhados)
- **Módulos parciais** (arquivos com `_` no nome)

## ▶️ Como compilar

```bash
# Instalar o SASS (se necessário)
npm install -g sass

# Compilar uma vez
sass sass/styles.scss styles.css

# Compilar em modo watch (recompila ao salvar)
sass --watch sass/styles.scss:styles.css
```
