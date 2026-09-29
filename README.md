# antoniorappleton.github.io

Página inicial da Comunidade CSJ Ramalhão — reencaminha para as apps:

- [Direção de Turma](https://antoniorappleton.github.io/direcao-turma/)
- [Scriptorium](https://antoniorappleton.github.io/scriptorium/)
- outras apps futuras (adicionar um `app-tile` em `index.html`)

Sem login nem build: é só HTML/CSS estático na raiz do repositório.

## Passos para pôr a funcionar

1. Criar o repositório no GitHub com o nome exato `antoniorappleton.github.io` (nome especial —
   é o único que o GitHub Pages serve na raiz do domínio; qualquer outro nome de repo fica
   sempre em `antoniorappleton.github.io/<nome-do-repo>/`).
2. Fazer push deste código para a branch `main`.
3. Settings → Pages → Source → branch `main`, pasta `/ (root)`. Sem workflow necessário
   (não há build, é HTML estático servido diretamente).

## Adicionar uma nova app

Editar `index.html` e substituir o cartão "Em breve" por um `<a class="app-tile" href="...">`
igual aos existentes.
