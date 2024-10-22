# sudo
    Sudo
O comando `sudo` (superuser do) no Linux *permite que usuários executem comandos com privilégios de administrador `root`*. **Ele é usado para realizar tarefas que exigem permissões elevadas, como instalar software ou modificar configurações do sistema.**
#

## apt
     apt
  O comando `apt` (Advanced Package Tool) no Linux **é um gerenciador de pacotes usado para instalar, atualizar e remover software** em distribuições baseadas em Debian, como o Ubuntu. Ele simplifica a gestão de pacotes, resolvendo automaticamente dependências necessárias. Muitas ações com `apt` requerem `sudo`, mas não todas.

  
### update
    apt update
  O comando `apt update` no Linux é utilizado para atualizar a lista de pacotes disponíveis nos repositórios configurados no sistema. **Ele baixa** informações sobre novas versões de pacotes e suas dependências, garantindo que o gerenciador de pacotes esteja ciente das atualizações disponíveis.

### upgrade
    apt upgrade
  O comando `apt upgrade` no Linux é utilizado para atualizar todos os pacotes instalados no sistema para suas versões mais recentes, conforme informado pelos repositórios. **Ele baixa e instala** as novas versões dos pacotes, mantendo suas configurações atuais. Geralmente é usado após o `apt update` para garantir que o sistema esteja atualizado.
    
### full upgrade
    apt full-upgrade
  O comando `apt full-upgrade` no Linux atualiza todos os pacotes instalados para suas versões mais recentes, similar ao `apt upgrade`, mas com uma diferença: ***ele também pode remover ou substituir pacotes se necessário para concluir a atualização***. Isso garante que o sistema fique completamente atualizado, mesmo que seja preciso fazer mudanças mais drásticas nas dependências.

### dist upgrade
    apt dist-upgrade
  O comando `apt dist-upgrade` no Linux é usado para atualizar pacotes instalados, assim como o `apt upgrade`, ***mas com a capacidade adicional de instalar, remover ou substituir pacotes para resolver dependências complexas***. Ele é útil em atualizações maiores, como quando uma nova versão do sistema é lançada.

### autoremove
    apt autoremove
  O comando `apt autoremove` no Linux é utilizado para remover pacotes e dependências que foram instalados automaticamente, **mas que não são mais necessários**, geralmente após a desinstalação de outros pacotes. Ele ajuda a liberar espaço no sistema ao limpar pacotes órfãos.

### autoclean
    apt autoclean
  O comando `apt autoclean` no Linux ***remove arquivos de pacotes `.deb` armazenados em cache que não são mais necessários***, como versões antigas de pacotes que já foram atualizados. Isso ajuda a liberar espaço no disco sem afetar os pacotes instalados.
#

## reboot
    sudo reboot
  O comando `sudo reboot` no Linux ***reinicia o sistema imediatamente, encerrando todos os processos e reinicializando o computador***. Ele requer privilégios de administrador `sudo` para garantir que o sistema seja reiniciado de forma segura.
#

# history
    history
  O comando `history` no Linux exibe uma lista dos comandos recentemente executados no terminal, permitindo que o usuário veja e reutilize esses comandos.

ls
ls -l h a
pwd
cd
/
azul escuro - diretório
marca texto verde - perigo
azul claro - atalho
-v

