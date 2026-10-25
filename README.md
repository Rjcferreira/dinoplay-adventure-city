# Cidade das Aventuras

Explora a cidade, ganha moedas e compra veículos.

Repositório independente para a plataforma [DinoPlay](https://rjcferreira.github.io/dino-color-quiz/).

## Estado da migração

O jogo já pode ser versionado, validado e executado a partir deste repositório. Nesta primeira extração conserva uma cópia do motor nativo legado para manter a jogabilidade exatamente igual. O objetivo seguinte é reduzir gradualmente o motor ao código exclusivo deste jogo e trocar o armazenamento legado pelo SDK do DinoPlay.

## Desenvolvimento

```bash
node scripts/validate.mjs
python -m http.server 8080
```
