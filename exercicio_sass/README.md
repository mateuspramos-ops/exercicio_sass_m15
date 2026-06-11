# Exercício SASS

Conversão do CSS do projeto para SASS, com variáveis e módulos.

## 📁 Estrutura

```
exercicio_sass/
├── sass/
│   ├── main.scss          → arquivo principal (importa os módulos)
│   ├── _variables.scss    → variáveis (cores, fontes, espaçamentos)
│   ├── _reset.scss        → reset global
│   ├── _header.scss       → cabeçalho e menu
│   ├── _products.scss     → grid de produtos e botão
│   └── _responsive.scss   → media queries
├── index.html             → página original do professor
├── styles.css             → CSS gerado pelo SASS (não editar)
├── package.json           → configuração do ambiente
└── README.md
```

## ▶️ Como compilar

```bash
# 1. Instalar o SASS
npm install

# 2. Compilar e observar mudanças automaticamente
npm run sass

# Ou diretamente:
sass --watch sass/main.scss:styles.css
```
