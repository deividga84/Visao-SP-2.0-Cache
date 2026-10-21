# Estrutura do cache do jogo

Esta pasta reproduz **somente a estrutura de diretórios** encontrada no `cache.zip` usado pela instalação inicial. Os arquivos binários, os dados do jogo e os logs não foram enviados para este repositório; cada diretório é mantido no Git por um `.gitkeep`, e a relação completa de caminhos e tamanhos está em [`CACHE_STRUCTURE.md`](CACHE_STRUCTURE.md).

## Origem identificada no código

- Download inicial do cache: <https://drive.usercontent.google.com/download?id=1nrwaHgLplRAk7X72yrERlH8qyRPnvGok&export=download&confirm=t>
- Atualizações posteriores: <https://pride-russia-game.ru/data/update.zip>
- Caminho de instalação no Android: `/storage/emulated/0/Android/data/com.nexion.online/files/`

O launcher grava temporariamente o download inicial como `cache.zip`, extrai o conteúdo na raiz acima e depois remove o ZIP. A pasta `downloand/` mantém essa grafia porque é exatamente o nome exigido pelo código do launcher. A pasta `texdb/` concentra a maior parte dos dados descompactados do cache.

## Pastas de primeiro nível

```text
SAMP/
Text/
Textures/
anim/
audio/
data/
downloand/
fonts/
logs/
models/
texdb/
```

Este repositório é um mapa estrutural, não uma distribuição do cache do jogo.
