
# **DIO | Resumos Git e GitHub**

#### Repositório para armazenar resumos sobre Git e GitHub.

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/)

## 💻 Resumos dos comandos

| Comando | Função |
| ------- | ------- |
|```git init```|Inicia um repositório local com o Git|
|```git clone <https://link-com-o-nome-do-repositório>```|Clona o conteúdo de um repositório remoto|
|```git branch <nome-da-branch>```|Cria uma ramificação do repositório, permitindo que várias pessoas façam alterações individualmente sem afetar o arquivo principal|
|```git push -u <local-remoto> <nome-da-branch>```|Envia as branches para o repositório remoto|
|```git branch --list```|Lista as ramificações (branches)|
|```git branch -d <nome-da-branch>```|Exclui uma ramificação (branch)|
|```git checkout <nome-da-branch>```|Sai de uma branch para outra|
|```git checkout -b <nome-da-branch>```|Cria uma branch e automaticamente vai para essa nova branch|
|```git status```|Informa o status dos arquivos no repositório|
|```git add <arquivo>```|Adiciona um arquivo para o commit (fase de stage)|
|```git add -A```|Adicona todos os arquivos do repositório local para o commit (fase de stage)|
|```git commit -m "mensagem do commit"```|Define um ponto de verificação, ou seja, salva as alterações do repositório local antes de enviá-los para o repositório remoto. A mensagem serve para "comentar" as alterações feitas nesse commit|
|```git diff```|Mostra as diferenças entre os arquivos no diretório de trabalho e na área de palco (área de stage)|
|```git log```|Exibe um registri de todos os commits feitos no repositório|
|```git push <repositório-remoto> <nome-da-branch>```|Envia os commits locais para o repositório remoto (**OBS: caso a branch seja recém criada, é preciso fazer o upload da branch com o seguinte comando: ```git push -u origin <nome-da-branch>```**)|
|```git pull <repositório-remoto>```|Recebe as alterações do repositório remoto e aplica as mesmas no repositório local (**OBS: Essa operação pode causar conflitos que só podem ser resolvidos manualmente**)|
|```git fetch```|Recupera todas as filiais e commits do repositório remoto, mescla com os arquivos locais|
|```git revert <código hash>```|Desfaz as alterações feitas de um commit (Explicação detalhada aqui: [Git Revert](https://www.freecodecamp.org/portuguese/news/10-comandos-do-git-que-todo-desenvolvedor-deveria-conhecer/#:~:text=manualmente.-,9.%20Git%20revert,-%C3%80s%20vezes%2C%20precisamos))|
|```git merge```|Integra a branch atual na branch principal (Explicação detalhada aqui: [Git Merge](https://www.freecodecamp.org/portuguese/news/10-comandos-do-git-que-todo-desenvolvedor-deveria-conhecer/#:~:text=10.-,Git%20merge,-Quando%20voc%C3%AA%20concluir))|
|```git rm <arquivo>```|Remove o arquivo especificado do controle de versão|
|```git config --global```|Faz alterações globais nas configurações|
|```git config --global user.name```|Altera o nome do usuário globalmente|
|```git config --global user.name```|Altera o email do usuário globalmente|
|```git config --list```|Visualiza as configurações existentes (é possível selecionar o escopo usando --local, --global ou --system)|
|```git config --global core.editor <nome_do_editor>```|Altera o editor de texto padrão|
|```git config --global alias.ex <exemplo>```|Cria um _alias_ para encurtar comandos longos|
## 💡 Importante Lembrar
- Para adicionar emojis em um, copiamos e colamos no arquivo
- É possível fazer alterações em arquivos do repositório remoto (GitHub) clicando no **"."**, sendo assim, será aberto um VS Code web.
- Para salvar os arquivos, é só usar a interface gráfica.

## 🔗 Links
- [Controlando Versões com Git e GitHub](https://www.casadocodigo.com.br/pages/sumario-git-github)
- [Documentação GitHub Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0-beta.4)
- [Ferramenta Geradora de .gitignore](https://www.toptal.com/developers/gitignore/)
- [Ferramenta Markdown Guide](https://www.markdownguide.org/)
- [Introducing Github O’Reilly](https://www.oreilly.com/library/view/introducing-github/9781491949801/)
- [Learning Git O'Reilly](https://www.oreilly.com/library/view/learning-git/9781098133900/?_gl=1*1k0j59z*_ga*MTc2ODczMTk1MS4xNjk4NDI5NjAw*_ga_092EL089CH*MTcwMTcxODU5OC4yLjEuMTcwMTcxODc3NS41My4wLjA.)