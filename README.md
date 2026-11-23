# Piano Assistant — versão inicial

## Arquivos do projeto
- `index.html` — aplicativo web.
- `manifest.webmanifest` — configuração da instalação como PWA.
- `sw.js` — cache básico do service worker.
- `README.md` — estas instruções.

## Publicar no GitHub Pages
1. Envie **os quatro arquivos individualmente** para a raiz do repositório.
2. Abra Settings → Pages.
3. Em Source, escolha `Deploy from a branch`.
4. Em Branch, escolha `main` e a pasta `/(root)`.
5. Salve e aguarde a publicação.

O arquivo `index.html` precisa ficar diretamente na raiz do repositório, não dentro de uma subpasta e não apenas dentro do ZIP.

## Usar no iPhone
Abra o endereço publicado no Safari. Para adicionar à tela inicial, use Compartilhar → Adicionar à Tela de Início.

## Observações e limitações
- Esta é uma primeira versão de demonstração, não o aplicativo completo planejado.
- O teclado virtual gera tons simples; não é uma reprodução realista de piano.
- O metrônomo, transposição e registros são recursos básicos.
- Os registros ficam no armazenamento local do navegador. Limpar os dados do Safari pode apagá-los.
- O detector de notas/acordes pelo microfone, análise avançada, avaliação de nível, cursos completos e análise de áudio ainda não estão implementados.
- Não inclui letras protegidas por direitos autorais.
- Nenhuma API paga ou serviço externo é necessário para esta versão.
