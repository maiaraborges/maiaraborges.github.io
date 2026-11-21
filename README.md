# Portfólio — Maiara Borges

Site estático (HTML, CSS e JavaScript em um único `index.html`), sem build e sem dependências.

## Estrutura

```
index.html          → o site inteiro (conteúdo, estilos e lógica)
favicon.svg         → ícone da aba
img/                → fotos
  mai-home.jpg        foto da home
  mai-sobre-google.jpg foto da aba Sobre
  vida/               fotos de "Fora da tela"
  logos/              logos das empresas (adicione aqui)
  wood/               telas e fotos do projeto Wood Identification (adicione aqui)
.nojekyll           → evita processamento do GitHub Pages
```

## Como editar o conteúdo

Abra o `index.html` e procure por **`EDITE AQUI`**:

- `CONTEUDO` → textos em português, projetos, trajetória, formação, cursos, links.
- `CONTEUDO_EN` → as traduções em inglês (só os textos).
- `TEXTOS` → textos fixos da interface (menus, botões, anotações da foto).

Imagens: coloque o arquivo na pasta `img/` e escreva o caminho no campo `src` ou `logo`.
Certificados: cole o link no campo `certificado` do curso.

## Publicar no GitHub Pages (grátis)

1. Crie uma conta em github.com e clique em **New repository**.
2. Dê um nome (ex.: `portfolio`), deixe **Public** e crie.
3. Clique em **uploading an existing file** e arraste **todo o conteúdo desta pasta** (o `index.html` precisa ficar na raiz, não dentro de outra pasta).
4. Clique em **Commit changes**.
5. Vá em **Settings → Pages**. Em *Source*, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)** e salve.
6. Em 1–2 minutos o site estará em `https://SEU-USUARIO.github.io/portfolio/`.

Para atualizar: edite o arquivo no GitHub (ícone de lápis) ou envie a nova versão. O site atualiza sozinho.

Dica: se o repositório se chamar `SEU-USUARIO.github.io`, o endereço fica `https://SEU-USUARIO.github.io`.

## Alternativa: Netlify

Em app.netlify.com/drop arraste esta pasta. Para atualizar, arraste de novo.
Também dá para conectar o repositório do GitHub no Netlify e cada alteração publica sozinha.

## Formulário de contato

O formulário abre o app de e-mail de quem envia, com a mensagem pronta para `maiara.borges2@gmail.com`.
Se quiser receber as mensagens direto (sem depender do app de e-mail), use o Netlify Forms ou o Formspree.

## Testar no computador

Basta abrir o `index.html` no navegador (duplo clique).
