# GabaritoExpress (PWA)

Gerador e leitor de cartão-resposta. Funciona offline depois do primeiro acesso.

## Publicar no GitHub Pages
1. Crie um repositório e envie **todo o conteúdo desta pasta** para a raiz (inclusive `.nojekyll` e a pasta `icons`).
2. Em *Settings → Pages*, escolha *Deploy from a branch*, branch `main`, pasta `/ (root)`.
3. Abra `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/` no celular (precisa ser https para a câmera ao vivo).
4. Instale: Android/Chrome → "Instalar app"; iPhone/Safari → Compartilhar → "Adicionar à Tela de Início".

## Atualizar uma versão
Depois de mudar qualquer arquivo, troque `VERSION` em `service-worker.js` (ex.: `v2`) para os aparelhos baixarem a novidade.

Os dados (chave, histórico) ficam salvos no navegador de cada aparelho.
