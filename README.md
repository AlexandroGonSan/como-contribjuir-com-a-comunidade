# como-contribjuir-com-a-comunidade
Tudo o que você precisa para contribuir coma comunidade
# O Que fazer
- faça um mapeamento de porta reverso da máquina local para dentro do container docker
- compartilhe comigo
# Git
- resolver a seguinte falha fatal no git, siga os passos
```
mkdir falhafatalgit
cd falhafatalgit
git init
touch file
git add file
git commit file
CTRL+Z
git commit -m "create file"
fatal: Unable to create './falhafatalgit/.git/index.lock': File exists.                                               
Another git process seems to be running in this repository, e.g.
an editor opened by 'git commit'. Please make sure all processes
are terminated then try again. If it still fails, a git process
may have crashed in this repository earlier:
remove the file manually to continue.
```
  > automatizar solução da falha
- mapear no git: `git submodule update --remote` para `git remote submodule update`
- definir `superproject` no contexto da pagina [Git - git-submodule Documentation](https://git-scm.com/docs/git-submodule)
  - enviar para eles e pedir para atualizarem a página e pedir para tornar a edição da página pública para pull requests
Para começar vá para: [Submitting Patches](https://github.com/git/git/blob/master/Documentation/SubmittingPatches)
O documento para alterar está aqui: [git-submodule(1): git-submodule - Initialize, update or inspect submodules](https://github.com/git/git/blob/master/Documentation/git-submodule.txt)
  - algo como um dicionario de termos para consulta
