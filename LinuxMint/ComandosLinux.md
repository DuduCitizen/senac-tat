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

# ls
    ls
O comando `ls` no Bash é usado para listar arquivos e diretórios dentro de um diretório. Quando você executa `ls`, ele exibe os arquivos e pastas presentes no diretório atual, ou em um diretório especificado.

### ls -l
    ls -l
Mostra uma listagem detalhada, incluindo permissões, número de links, proprietário, tamanho, e data/hora da última modificação.
#

### ls -a
    ls -a
Lista todos os arquivos, incluindo os arquivos ocultos (aqueles que começam com um ponto .).
#

### ls -lh
    ls -lh
Mostra a listagem detalhada com o tamanho dos arquivos em um formato legível (com unidades como KB, MB, etc.).
#

# pwd
    pwd
O comando pwd no Bash significa "print working directory" (imprimir diretório de trabalho). ***Ele exibe o caminho completo do diretório atual em que você está*** no terminal.
Exemplo:

    /home/usuario/documentos

# cd
    cd /
O comando cd no Bash significa "change directory" (mudar diretório). Ele é usado para navegar entre diretórios no sistema de arquivos.

    cd [diretório]
***Muda para o diretório especificado.***

- Exemplo: `cd /home/usuario/documentos` vai mudar para o diretório `/home/usuario/documentos`.
#

    cd ..
***Sobe um nível na hierarquia de diretórios.***

- Exemplo: Se você estiver em `/home/usuario/documentos`, ao digitar `cd ..`, você irá para `/home/usuario`.
#

    cd ~
***Vai diretamente para o diretório home do usuário.***

- Exemplo: cd ~ leva você ao seu diretório home, como `/home/usuario`.
#

    cd -
***Volta para o último diretório em que você estava antes de mudar.***
- Exemplo: Se você estava em `/var/log` e mudou para `/home/usuario`, ao executar `cd -`, você volta para `/var/log`.
#


# echo
    echo
O comando `echo` no Bash é usado para ***exibir uma mensagem ou o valor de uma variável no terminal.*** Ele simplesmente imprime o texto ou a informação que você passar como argumento.
#

# Parâmetros
### verbose
    -v
O parâmetro `-v` no Bash geralmente significa "verbose" (detalhado). ***Ele é usado para fazer com que um comando forneça mais informações sobre o que está fazendo***, ou seja, exiba saídas mais detalhadas durante sua execução.
#

# Cores comuns no Bash:
- Azul: ***Diretórios.***
- Verde: ***Arquivos executáveis*** (programas ou scripts com permissão de execução).
- Ciano (azul claro): ***Links simbólicos*** (atalhos para arquivos ou diretórios).
- Roxo: ***Arquivos compactados ou arquivos de imagem de disco*** (como `.tar, .gz, .zip, .iso`).
- Vermelho: ***Arquivos com permissão de execução especial*** (`setuid, setgid, sticky bit`) ***ou arquivos com erros de permissões.***
- Amarelo: ***Dispositivos*** (arquivos especiais, como dispositivos de bloco ou caracteres, por exemplo, `/dev/sda`).
- Cinza claro: ***Arquivos normais***(sem atributos especiais).
#

# Git
### git clone
    git clone [url do repositório]
O comando `git clone` no Bash ***é usado para copiar (clonar) um repositório Git remoto para o seu computador.*** Ele cria uma cópia completa do repositório, incluindo todos os arquivos, commits e branches.
#

### git config
    git config [opções] [chave] [valor]
O comando `git config` no Bash ***é usado para configurar as opções do Git em diferentes níveis.*** Com ele, você pode definir configurações globais, de repositório ou do sistema que afetam o comportamento do Git.
<br>

Exemplos de uso:
- Definir nome de usuário

        git config --global user.name "Seu Nome"

- Definir e-mail do usuário

        git config --global user.email "seuemail@exemplo.com"

- Verificar configurações

        git config --list
#

">"
">>"


head
tail
cat
tac
less
cp
mv
rm
