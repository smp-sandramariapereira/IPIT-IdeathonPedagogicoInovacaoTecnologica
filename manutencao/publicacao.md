# Publicação da página
A página estática usa somente index.html e assets/css/styles.css; não exige compilação.
Endereço previsto: https://smp-sandramariapereira.github.io/IPIT-IdeathonPedagogicoInovacaoTecnologica/index.html

## Habilitar GitHub Pages
No repositório, abra Settings → Pages.
Em Build and deployment, selecione **Deploy from a branch**.
Escolha **main** e **/ (root)** e salve.
Aguarde a implantação concluir e abra o endereço acima. A existência do arquivo não significa que o site esteja publicado.
Se já houver outra configuração de Pages, confira a origem antes de mudar. O arquivo .nojekyll permite servir os arquivos estáticos diretamente.

## Conferência
- Página inicial e estilo carregam no caminho /IPIT-IdeathonPedagogicoInovacaoTecnologica/index.html.
- Navegação chega às quatro seções.
- Materiais abrem no GitHub para leitura formatada; não há links para downloads ainda inexistentes.
- A seção de origem distingue artigo, acervo e adaptação.
- O conteúdo é utilizável em telas pequenas e por teclado.

Conteúdo educacional CC BY 4.0; código MIT, conforme [LICENSE](../LICENSE).

## Se aparecer 404
1. Confirme que Pages publica a branch main e a pasta raiz, e não docs/.
2. Confira a execução “pages build and deployment” na aba Actions. Aguarde conclusão e confira falhas nos jobs, se houver.
3. Abra o endereço exato indicado acima; ele é diferente do endereço do acervo IPIT_origin.
4. Após a implantação bem-sucedida, recarregue a página. Se o erro persistir, confira a URL exibida em Settings → Pages.

A mudança de pastas preserva index.html na raiz e o caminho citado pelo artigo.
