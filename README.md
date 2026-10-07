# Mapa Eleitoral de Gurupi

Site estático para GitHub Pages com votação para vereador em 2020 e 2024.

## Páginas
- `index.html`: candidatos, locais e seções em texto.
- `mapa.html`: mapa por candidato e ano.
- `comparativo-alana.html`: comparação de ALANA LINHARES CARVALHO entre 2020 e 2024.

## Publicar no GitHub Pages
1. Crie um repositório público.
2. Envie todo o conteúdo desta pasta para a raiz do repositório.
3. Abra Settings > Pages.
4. Selecione Deploy from a branch, branch main e pasta /root.
5. Aguarde a publicação.

## Preparar o mapa
O arquivo `data/locais-coordenadas.json` começa sem coordenadas.
1. Publique o site no GitHub Pages.
2. Abra `mapa.html`.
3. Clique em “Preparar coordenadas”.
4. Aguarde a busca dos locais.
5. Clique em “Baixar coordenadas JSON”.
6. Revise os pontos e substitua `data/locais-coordenadas.json` pelo arquivo baixado.
7. Faça novo commit.

A geocodificação automática deve ser usada apenas para preparar os dados. Confira os pontos antes da divulgação pública.

## Metodologia
- Fonte: arquivos de votação por seção do TSE.
- Município: Gurupi, Tocantins.
- Cargo: vereador.
- O comparativo de Alana cruza inicialmente os locais por nome normalizado.
- Votos por local não equivalem ao bairro de residência dos eleitores.
