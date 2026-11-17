# Portfolio — Alice Barroso

Portfólio pessoal de Alice Vitória Nunes Barroso de Aguiar, estudante de Ciência da Computação com foco em desenvolvimento de software e inteligência artificial.

## Arquivos

- `index.html` — conteúdo semântico, metadados e links.
- `styles.css` — identidade visual responsiva e ilustrações CSS conceituais.
- `favicon.svg` — ícone do site.

O site usa HTML, CSS e um pequeno trecho de JavaScript para atualizar o ano no rodapé. Não exige instalação de dependências nem processo de build. As fontes DM Sans, Manrope e DM Mono são carregadas pelo Google Fonts, com fontes de sistema como alternativa. As visualizações dos projetos são elementos gráficos conceituais, não capturas de tela ou resultados dinâmicos.

## Visualizar localmente

Abra `index.html` no navegador ou sirva a raiz do repositório:

```bash
python -m http.server 8000
```

Acesse <http://localhost:8000>.

## Publicar com GitHub Pages

1. Revise as alterações e crie um commit na branch principal.
2. Envie a branch ao GitHub com `git push origin main` (sem force push).
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione `main` e a pasta `/(root)`, e salve.
5. Aguarde a publicação e teste o endereço indicado em Settings → Pages. O deploy só está confirmado depois que o site público abrir corretamente.

O repositório remoto continua com o nome atual `Portifolio`. Se Alice decidir renomeá-lo, faça isso manualmente em **Settings → General → Repository name**, após revisar a mudança. Com o nome `Portfolio`, o endereço esperado será <https://alicevbarroso.github.io/Portfolio/>; confirme o endereço real após o deploy.
