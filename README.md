# Exercício de GitHub

![Git logo](https://cdn.icon-icons.com/icons2/2108/PNG/512/git_icon_130933.png)

### Ações

1. Criei o arquivo `dados/arluza.txt` e coloquei nele um texto;
2. Adicionei uma linha de código em `arquivos.js`;
3. Carreguei uma imagem na pasta `imagens`.

### Procedimentos

[x] Passo 1. Usar o `git clone https://github.com/arleysouza/esof` o comando para puxar o projeto para a sua máquina.

[x] Passo 2. Criei um branch com nome samres a partir da branch main, a primeira coisa que fazemos é `git checkout  -b " samres "`, assim criando uma branch esse comando além de criar a branch já entra nela com o checkout.

[x] Passo 3. Adicionei o arquivo TXT, uma linha no arquivos.js e carregue a imagem Git na pasta imagem na branch samres.

[x] Passo 4. Para finalizar alterei o arquivo README.md. Usei o comando `git add . para colocar o arquivo na área de stagging e dei um git commit` pare a dar o commit no repositório.

[x] Passo 5. Enviar o arquivo para repositório `git push`.

```javascript
samuc@LAPTOP-1UVA8F1I MINGW64 ~/esof (samres)
$ git log
commit 4de482553f1761ba846968f811983df64a5f7b35 (HEAD -> samres, origin/samres)
Author: shimu192 <samucosta58@gmail.com>
Date:   Mon Jun 21 15:47:06 2021 -0300

    primeiro commit

commit cd8eddedf6af081060ede46385ef53675700b784 (origin/main, origin/lindal, origin/HEAD, main)
Author: arleysouza <arley.ferreira.souza@gmail.com>
Date:   Mon Jun 21 12:34:28 2021 -0300

    caminho

commit 872349fa4709205db181986aab7a6695346d47ae
Author: arleysouza <arley.ferreira.souza@gmail.com>
Date:   Mon Jun 21 12:31:39 2021 -0300

$ git status
On branch samres
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   arquivos.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        dados/samres.txt
        imagens/git.png

no changes added to commit (use "git add" and/or "git commit -a")

```
