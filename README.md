# Arquivo de imagens — ZXKO e Dazero

Captura de 14/10/2026 das imagens ligadas aos catálogos públicos e aos espelhos/APKs analisados. Os binários foram mantidos byte a byte como recebidos/extraídos, sem redimensionamento ou recompressão. Arquivos com SHA-256 idêntico compartilham uma única cópia em `image-originals/`.

## Resumo

- URLs públicas de imagem inventariadas: 11.519.
- URLs que retornaram imagem: 11.488.
- URLs indisponíveis ou que retornaram conteúdo não-imagem: 31; status e URL original estão no manifesto/CSV.
- Imagens estáticas já extraídas dos APKs e dos espelhos: 275 entradas de origem.
- Arquivos únicos neste pacote: 9.856 (2.567 GiB), deduplicados por SHA-256.
- Catálogo consolidado: 2.135 grupos de itens públicos.

## Índices

- [CSV com links originais e raw, app, status, hash, item, IDs e páginas](data/image-download-links.csv)
- [Manifesto completo de cada URL e tentativa](data/image-download-manifest.json)
- [Catálogo público completo com links locais/GitHub de imagem](data/published-items-with-hosted-images.json)
- [Manifesto das imagens estáticas dos APKs/espelhos](data/local-static-image-manifest.json)
- [Resumo por domínio e erros](data/image-download-summary.md)

Os caminhos binários são `image-originals/<prefixo>/<sha256>.<extensão>`. O link direto para cada arquivo pode ser composto usando `https://raw.githubusercontent.com/Guihjzzz/zxko-dazero-image-archive/main/` + o valor de `RepositoryFile` no CSV/JSON.

## Origem e direitos

As URLs de origem e os apps associados estão nos índices. Os arquivos publicados são cópias para análise dos itens que estavam publicamente acessíveis; esta coleção não declara autoria nem transfere ou concede direitos sobre imagens de terceiros. Consulte os respectivos autores e fontes antes de reutilizar ou redistribuir.
