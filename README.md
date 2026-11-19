# Redphone

Landing page responsiva da loja Redphone, de João Pessoa–PB, em português, feita com HTML, CSS e JavaScript, sem dependências de build.

## Abrir localmente

Abra `index.html` no navegador. Para servir via HTTP, execute na pasta do projeto:

```sh
python3 -m http.server 8000
```

Acesse http://localhost:8000.

## Identidade da marca

Preto, vermelho e branco, logo e apresentação de iPhone, MacBook, iPad e Watch baseados no perfil público @oficial.redphone. Referências em `brand-sources.json`.

## Funcionalidades

- Catálogo de 31 modelos: linhas iPhone 11 a 18 Pro Max, incluindo mini, Plus, Pro, Pro Max, Air, 16e e 17e.
- Carrossel com avanço automático, pausa, setas, deslize no celular e navegação por teclado.
- Filtros combinados por geração e categoria, com respeito à preferência de movimento reduzido.
- Imagens oficiais do catálogo com frente e verso e fundo transparente.
- Contato pelo Direct do perfil oficial @oficial.redphone, conforme a bio da marca.
- Perguntas frequentes e layout para celular e desktop.

## Personalização

O conteúdo, os estilos e os scripts estão em `index.html`. Os botões de consulta apontam para o Instagram oficial, onde as compras são feitas pelo Direct. Os links do Instagram levam ao perfil oficial https://www.instagram.com/oficial.redphone/. Consulte `image-sources.json` para a origem das imagens do catálogo. A imagem principal foi aprimorada com IA a partir da imagem fornecida pelo responsável pela loja.

## Publicação

Os modelos e as fontes das imagens também estão registrados em `catalog.json` e `image-sources.json`.

Os arquivos são estáticos. Publique o conteúdo da raiz em uma hospedagem estática; não é necessário instalar pacotes nem executar um build.

iPhone é uma marca da Apple Inc. A loja é independente. As imagens não indicam disponibilidade em estoque; consulte a loja.

## Refinamento de design

Visual refinado com a Taste Skill 2.5.1: tipografia, alinhamento, contraste, botões, movimento de entrada e interações. As cores da Redphone e o carrossel de 5 segundos foram preservados. A checagem de texto passou sem falhas ou avisos; a validação visual automática completa não foi executada.
