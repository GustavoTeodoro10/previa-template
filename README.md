# Template de prévia TeoCode

Base para as prévias enviadas a leads em prospecção ativa. Já inclui o rastreamento de visitas (GoatCounter), então toda prévia criada a partir daqui sai com analytics por padrão.

## Como criar uma prévia nova

1. Nesta página, clique em **Use this template → Create a new repository**.
2. Nome do repositório: use o padrão `TipoNomeDoLead` (ex.: `PsicoMariaSilva`). O nome vira o caminho no painel de analytics.
3. Deixe o repositório **Public** (necessário para o GitHub Pages gratuito).
4. Edite `index.html` e coloque as imagens em `assets/`.
5. Ative o site em **Settings → Pages → Deploy from a branch → `main` / `(root)`**.
6. Link da prévia: `https://gustavoteodoro10.github.io/NomeDoRepositorio/`

## Antes de enviar o link

- [ ] O `<script data-goatcounter=...>` continua antes do `</body>`.
- [ ] Abra a prévia **uma vez** com `#toggle-goatcounter` no final da URL, em cada navegador/dispositivo seu, para suas visitas não contarem.
- [ ] Placeholders (`NOME DO NEGÓCIO`, `DDDNUMERO`, textos de exemplo) substituídos.

## Ver as visitas

Painel: https://teocode.goatcounter.com (login necessário). Cada prévia aparece pelo caminho, por exemplo `/PsicoMariaSilva/`.

Se o site tiver outras páginas além do `index.html`, o mesmo script precisa estar em cada uma.
