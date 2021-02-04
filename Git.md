# Git e GitHub
---

[Git](https://git-scm.com/docs) é um Software de Contolo de Versão, já o [GitHub](https://github.com), é uma plataforma, de rede social para programadores.

---

### Git

Comando | Funcionalidade
------------ | ------------
git init | Inicia a linha do tempo
git add . | Adiciona ou atualiza mudanças para irem para a linha do tempo
git commit -m "texto" | Cria um ponto na linha do tempo
git remote add origin `link`| Adiciona o nosso projeto a um repositório 
git push | Adiciona todas as alterações ao repositório
git commit -am "text" | Adiciona os aquivos para a linha do tempo e cria um ponto
git log | Visualiza os pontos na linha do tempo / commit
git status | Informa o estado das alterações do projeto
git show | Apresenta determinado pronto na história
git branch | Mostra os nossos branches
git branch feature/login | Cria um novo ramo, que não interfere no `master`
git checkout feature/login | Leva-nos até à branch `feature/login`
git checkout -b teste | Cria e leva-nos à branch `teste`
git merge feature/login | Une o branch `feature/login` ao `master`
git branch -D feature/login | Apaga a branch `feature/login`
git clone | Clonar projeto / repositório
git pull | Puxar do repositório remoto, alguma modificação feita por outra pessoa
git checkout be283r72r8bfidsufuf4783643888vddw2 -- index.html | Permite pegar em arquivos de outros commits. Com o `git log` encontramos o commit que queremos pegar  
git checkout -- webpack.config.js | Recupera o arquivo apagado, caso não tenhamos feito nenhum commit
git reset | Desfaz as alterações locais e reverte tudo para o último commit
git stash | Guarda as alterações noutro diretório de trabalho





