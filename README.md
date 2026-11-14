# VoiceClone Lab v7

Dashboard estático para GitHub Pages, com 99 áudios (33 humanos, 66 sintéticos).

Abra `index.html` diretamente no navegador. Os dados estão incorporados em `dataset.js`; nenhum servidor ou API é necessário.

## Publicação

Envie todos os arquivos e a pasta `assets/` para a raiz do repositório GitHub e ative Pages na branch main / root.

## Metodologia e limitações

O índice acústico é heurístico, não é speaker similarity validada. A duração indicada nos filtros é nominal da referência.
Os 66 arquivos sintéticos foram analisados com decodificação mono 8kHz, STFT 512, estimativa aproximada de F0 por autocorrelação. Os 33 arquivos anteriores conservam métricas do pipeline anterior. Para comparação científica entre coortes, reprocessar todos com metodologia idêntica.

Não foram inventados prompts ou transcrições para os 66 áudios.
