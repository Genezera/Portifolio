# Portfólio (Projetos)

Este repositório contém projetos prontos para você usar como portfólio no GitHub (cada projeto em uma pasta, com README próprio e demo abrindo no navegador).

## Projetos

- **TaskFlow Kanban** — quadro Kanban com drag-and-drop, edição e persistência em LocalStorage  
  Pasta: `projects/taskflow-kanban/` • Demo: `projects/taskflow-kanban/index.html`
- **ShopCart UI** — catálogo com filtros/pesquisa, carrinho e persistência em LocalStorage  
  Pasta: `projects/shopcart-ui/` • Demo: `projects/shopcart-ui/index.html`
- **Weatherly** — dashboard de clima com busca de cidades (Open‑Meteo) e cache local  
  Pasta: `projects/weatherly/` • Demo: `projects/weatherly/index.html`

## Como rodar

Você pode abrir o `index.html` de cada projeto diretamente no navegador. Se algum navegador bloquear requisições (no projeto de clima), rode com um servidor local:

```bash
python -m http.server 5173
```

Depois acesse: `http://localhost:5173/`

## Como transformar em “vários repositórios”

Se você quiser deixar “1 projeto = 1 repo” no GitHub:

1. Crie um novo repositório no GitHub.
2. Copie a pasta do projeto (ex.: `projects/taskflow-kanban/`) para uma pasta vazia e faça commit.
3. Publique esse repositório.
