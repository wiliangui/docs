# PrimePix Docs (estilo Mintlify)

Este repositório é um template pronto para você publicar uma documentação no estilo do `docs.versellpay.com`.

## Arquivos principais
- `docs.json` -> configuração do site (navegação, tema, cores, links)
- `openapi.json` -> sua spec OpenAPI (usada para gerar a seção "API Reference")
- `index.mdx` e demais `*.mdx` -> páginas do guia

## Rodar localmente (Mintlify CLI)
1) Instale a CLI:
   npm i -g mintlify

2) Na raiz do projeto:
   mintlify dev

## Publicar
- Suba este repo no GitHub e conecte no Mintlify (ou use o dashboard).
- Configure seu domínio: `docs.primepix.me` (ou o que preferir).
