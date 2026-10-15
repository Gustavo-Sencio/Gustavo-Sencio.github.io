# Página pessoal — Gustavo Souza

Página estática em português, preparada para o GitHub Pages. Não precisa de instalação, dependências, compilação ou servidor próprio.

## Visualizar no Windows

Extraia o ZIP e abra `index.html` no navegador. Para editar, abra esta pasta no VS Code. O conteúdo está em `index.html`; o visual está em `style.css`.

## Publicar pelo navegador no GitHub

1. Entre na sua conta em https://github.com e crie um repositório **público** chamado `Gustavo-Sencio.github.io`. Ative a criação do README ao criar o repositório para facilitar o envio dos arquivos.
2. No repositório, clique em **Add file → Upload files**. Envie os arquivos extraídos deste pacote, incluindo `index.html`, `style.css` e `favicon.svg`. Eles precisam estar na raiz do repositório, sem a pasta `pagina-pessoal` envolvendo os arquivos. Confirme em **Commit changes**.
3. Acesse **Settings → Pages**.
4. Em **Build and deployment → Source**, selecione **Deploy from a branch**.
5. Escolha o branch **main** e a pasta **/ (root)**. Clique em **Save**.
6. Acompanhe a publicação na aba **Actions**. A página será acessível em `https://Gustavo-Sencio.github.io/`. A primeira publicação pode levar alguns minutos.

O arquivo `.nojekyll` é opcional nesta página; se ele não aparecer no seletor do Windows, isso não impede a publicação destes arquivos HTML/CSS.

Se já existir um repositório com esse nome, revise seu conteúdo antes de enviar estes arquivos para evitar substituir uma página anterior. Um site de projeto também pode usar outro nome de repositório e ficará em `https://Gustavo-Sencio.github.io/NOME-DO-REPOSITORIO/`.

## Personalizar

- Edite textos, publicações e links em `index.html`.
- Ajuste cores e tamanhos em `style.css`; as cores principais ficam em `:root`.
- O link do Lattes e o e-mail foram obtidos do currículo acadêmico fornecido.
- GitHub: https://github.com/Gustavo-Sencio
- Repositório recomendado: `Gustavo-Sencio.github.io`.
- Endereço após a publicação: https://gustavo-sencio.github.io/
- Não foram incluídos PDFs dos currículos: um deles contém endereço residencial, telefone e outros dados pessoais. Para oferecer um PDF público, prepare uma versão específica para o site.
- Os dados acadêmicos correspondem aos currículos fornecidos em outubro de 2026. Atualize formação e experiência conforme necessário.

Não há serviços de terceiros, coleta de dados, formulários, fontes remotas ou JavaScript. O link de contato abre o aplicativo de e-mail do visitante.

Documentação oficial: https://docs.github.com/pt/pages/quickstart
