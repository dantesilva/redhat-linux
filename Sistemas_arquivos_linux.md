# Entendendo o sistema de arquvos no Linux

FHS -> Hierarquia do sistema de arquivos

## Para ter ajuda no prório Linux

#man 7 hier (como root)

## Tabela RHEL8

/ -> Diretorio raiz

/bin -> Essencial durante o boot. Se econtra programas executaveis para reparar o sistema em modo minimo.

/boot -> Todos arquivos necessários para inicialização do kernel.

/dev -> Arquivo de dispostivos. Para acessar dispositivos fisicos (HD, SSD, Pendrive, etc..).

/etc -> Arquivos de configuração usados por programas e serviços. Essencial durante o boot.

/home -> Diretório padrão dos usuários.

/root -> Diretório padrão do usuário raiz.

/lib /lib64 -> Bibliotecas compartilhadas usadas pelo diretório  /boot, /bin. /sbin .

/media /mnt -> Diretórios usados para montar dispositivos na árvore de arquivos do sistema.

/opt -> Usados para pacotes opcionais.

/proc -> Diretório usado pelo sistema proc. Arquivo do sistema para dar informações do Kernel.

/run -> Contém informações específicas de usuários e processos desde o último boot.

/sbin -> Como /bin, mas para comandos de administração do sistema, que não são utilizados por usuários regulares.

/srv -> Diretório usado para dados e serviços, tais como NFS, FTP, HTTP.

/sys -> Usado para interagir com dispositivos de Hardware que são gerenciados pelo Kernel.

/tmp -> Arquivos temporários, que podem ser deletados na próxima reinicialização.

/var -> Diretório que muda de tamanho dinamicamente, tal como arquivos de log, email, arquivos de spool (impressora).

### Para mostrar toda a árvore de diretórios

#ls / 









