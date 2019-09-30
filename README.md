# Minhas configs para desenvolvimento no Linux

Hi! I'm your first Markdown file in **StackEdit**. If you want to learn about StackEdit, you can read me. If you want to play with Markdown, you can edit me. Once you have finished with me, you can create new files by opening the **file explorer** on the left corner of the navigation bar.

## Ubuntu :D

### Fonte
- Instalar a fonte no Linux: [https://github.com/belluzj/fantasque-sans](https://github.com/belluzj/fantasque-sans)
- Alterar nas configs do terminal do Linux para usar a fonte acima;
- Para alterar a fonte no vim, só seguir os passos abaixo, pois esta alteração já consta no $HOME/.vimrc

### Instalar o gerenciador de Plugins - Vim-plugin

Instalar conforme indicado aqui: [https://github.com/junegunn/vim-plug](https://github.com/junegunn/vim-plug)

### Configurando o vim

- Inserir todas as linhas do arquivo [.vimrc](https://github.com/NewHenriqueSouza/vim_config/blob/master/.vimrc ".vimrc") deste repo no arquivo $HOME/.vimrc
- Após isto, abrir o vim e digitar o seguinte comando: 

> PlugInstall


### Configurando o tmux

- Inserir todas as linhas do arquivo [.tmux.config](https://github.com/NewHenriqueSouza/vim_config/blob/master/.tmux.config ".tmux.config")  deste repo no arquivo $HOME/.vimrc
- Executar o reload das configs do tmux executando o comando a seguir: 

> tmux source-file ~/.tmux.conf

### Configuração do Bash

- Inserir as configs abaixo no final do arquivo~/.bashrc

1. Este comando serve para desativar o "lock" do bash que acontece no Ctrl + S

> stty -ixon


## Softwares - Maior parte linux :D

### Produtividade
- Boosternote [https://boostnote.io/](https://boostnote.io/) - Ferramenta para criar snippets
- Postman [https://www.getpostman.com/](https://www.getpostman.com/) Fazer requisições Http

### Internet
- Chrome [https://www.google.com/intl/pt-BR/chrome/](https://www.google.com/intl/pt-BR/chrome/) - Navegador

### Multimidia
- Pinta [https://pinta-project.com/pintaproject/pinta/](https://pinta-project.com/pintaproject/pinta/) - Editor de imagem
- Shutter [https://www.cyberciti.biz/open-source/linux-screenshot-program-tool/](https://www.cyberciti.biz/open-source/linux-screenshot-program-tool/) - Ferramenta de prints

### Som e vídeo
- VLC [https://www.videolan.org/vlc/index.html](https://www.videolan.org/vlc/index.html) - Mídia num geral
- Spotify [https://www.spotify.com/pt/](https://www.spotify.com/pt/) - Música né :D

### Utilitários node
- NVM [https://github.com/nvm-sh/nvm](https://github.com/nvm-sh/nvm) - Instalar multiplas versões do node

### Utilitários de sistema
- Stacer [https://github.com/oguzhaninan/Stacer](https://github.com/oguzhaninan/Stacer) Gerenciamento do uso do disco, memoria, e etc...
- Caffeine [https://launchpad.net/caffeine](https://launchpad.net/caffeine) - Manter a máquina acordada 
- CopyQ [https://github.com/hluk/CopyQ](https://github.com/hluk/CopyQ) - Gerenciador do clipboard

### Editores
- Visual Studio Code [https://code.visualstudio.com/](https://code.visualstudio.com/)
- Vim [https://www.vim.org/](https://www.vim.org/) Melhor editor :D

### Ambiente de desenvolvimento
- Docker [https://docs.docker.com/install/linux/docker-ce/ubuntu/](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
- Minikube https://github.com/kubernetes/minikube - Rodar kubernetes localhost

### Utilitários de linha de comando
- tldr [https://tldr.sh/](https://tldr.sh/) Utilitário parecido com o man do linux, só que mais direto e mais simples
- YADM [https://github.com/TheLocehiliosan/yadm](https://github.com/TheLocehiliosan/yadm) - Gerenciados de .[dot]Files
- fzf [https://github.com/junegunn/fzf](https://github.com/junegunn/fzf) Maior buscador do mundo :D
- ultisnips [https://github.com/SirVer/ultisnips](https://github.com/SirVer/ultisnips) - Ferramenta de snippets em linha de comando
- Inav [https://lnav.readthedocs.io/en/latest/](https://lnav.readthedocs.io/en/latest/) Gerenciar arquivos de logs, bem útil :D
- fkill [https://github.com/sindresorhus/fkill-cli](https://github.com/sindresorhus/fkill-cli) Melhor kill process
- how2 [https://github.com/santinic/how2](https://github.com/santinic/how2) Buscador no Stackoverflow
- ctop [https://github.com/bcicen/ctop](https://github.com/bcicen/ctop) Interace com métricas dos containers
- Pet https://github.com/knqyf263/pet Snipets simples para linha de comando
- caniuse [https://github.com/sgentle/caniuse-cmd](https://github.com/sgentle/caniuse-cmd) Verificar se algum recurso é compatível com o navegador especifico
- release-it [https://github.com/release-it/release-it](https://github.com/release-it/release-it) Automatizar tarefas de CI, versionamento automatico, etc
- httpie [https://github.com/jakubroztocil/httpie](https://github.com/jakubroztocil/httpie) Http Client igual o curl, só que para humanos :D
- JsonServer [https://github.com/typicode/json-server](https://github.com/typicode/json-server) Serve um json como uma API
- MailHog [https://blog.rocketseat.com.br/testando-emails-mailhog-node-docker/](https://blog.rocketseat.com.br/testando-emails-mailhog-node-docker/) Servidor SMTP pra poder testar o envio de e-mails, só seguir o tutorial ai de cima
