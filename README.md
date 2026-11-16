# O Seu iPhone

Landing page responsiva da loja O Seu iPhone, de João Pessoa–PB, em português, feita com HTML, CSS e JavaScript, sem dependências de build.

## Abrir localmente

Abra `index.html` no navegador. Para servir via HTTP, execute na pasta do projeto:

```sh
python3 -m http.server 8000
```

Acesse http://localhost:8000.

## Identidade da marca

Azul-marinho e branco, logo e posicionamento de produtos e assistência Apple baseados no perfil público @oseuiphone. Referências em `brand-sources.json`.

## Funcionalidades

- Catálogo de 31 modelos: linhas iPhone 11 a 18 Pro Max, incluindo mini, Plus, Pro, Pro Max, Air, 16e e 17e.
- Carrossel com avanço automático, pausa, setas, deslize no celular e navegação por teclado.
- Filtros combinados por geração e categoria, com respeito à preferência de movimento reduzido.
- Imagens oficiais do catálogo com frente e verso e fundo transparente.
- Contato pelo perfil oficial @oseuiphone no Instagram, até a confirmação do WhatsApp da marca.
- Perguntas frequentes e layout para celular e desktop.

## Personalização

O conteúdo, os estilos e os scripts estão em `index.html`. Os links de contato apontam para https://www.instagram.com/oseuiphone/. Consulte `image-sources.json` para a origem das imagens do catálogo. A imagem principal foi aprimorada com IA a partir da imagem fornecida pelo responsável pela loja.

## Publicação

Os modelos e as fontes das imagens também estão registrados em `catalog.json` e `image-sources.json`.

Os arquivos são estáticos. Publique o conteúdo da raiz em uma hospedagem estática; não é necessário instalar pacotes nem executar um build.

iPhone é uma marca da Apple Inc. A loja é independente. As imagens não indicam disponibilidade em estoque; consulte a loja.
