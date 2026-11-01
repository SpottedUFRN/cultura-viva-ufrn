# Cultura Viva na UFRN — Site v6.2

Site estático preparado para GitHub Pages.

## Publicação

1. Crie um repositório no GitHub, por exemplo `cultura-viva-ufrn` (público no plano GitHub Free).
2. Extraia o ZIP e envie **todos os arquivos e pastas para a raiz** do repositório, mantendo `index.html` na raiz.
3. No repositório, acesse **Settings > Pages**.
4. Em **Build and deployment > Source**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/(root)` e clique em **Save**.
6. Abra o endereço apresentado na seção Pages após a publicação (em geral `https://SEU-USUARIO.github.io/cultura-viva-ufrn/`).

## Estrutura

- `index.html`: página inicial
- `assets/`: estilo, scripts e ícone
- `documentos/`: PDFs para consulta e download
- `.nojekyll`: impede processamento Jekyll desnecessário

Não use o arquivo de visualização offline como index; ele é destinado apenas a visualização local.

## Atualizações

Envie versões dos arquivos ao mesmo repositório e faça commit. A publicação é atualizada a partir da branch configurada.
