# CTDZ — Advocacia e Assessoria

Primeira versão de uma página institucional responsiva, feita com HTML5, CSS3 e JavaScript puro. Não utiliza frameworks, bibliotecas externas, fontes remotas ou serviços de terceiros.

## Estrutura

```text
.
├── index.html
├── assets/
│   ├── css/styles.css
│   ├── js/main.js
│   └── images/
└── README.md
```

A pasta `assets/images/` está reservada para imagens e materiais da marca quando forem fornecidos.

## Visualizar localmente

Abrir `index.html` no navegador. Também é possível iniciar um servidor local no terminal, dentro desta pasta:

```bash
python3 -m http.server 8000
```

Depois acessar `http://localhost:8000` no navegador. Para encerrar o servidor, pressionar `Ctrl+C` no terminal.

## Personalização

As cores, fontes, largura do conteúdo e espaçamento principal estão definidos como variáveis no início de `assets/css/styles.css`. Os textos provisórios de áreas, perfil profissional e contato em `index.html` serão atualizados após confirmar os dados oficiais. A pasta de imagens está criada para receber materiais de marca aprovados.

## Acessibilidade e responsividade

A página inclui regiões semânticas, link para pular ao conteúdo, foco visível, navegação adaptada a telas pequenas, botão de menu com estado acessível, suporte à tecla `Escape` e preferência por movimento reduzido. A apresentação se adapta a computadores, tablets e celulares.
