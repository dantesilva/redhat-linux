
## Saber arquitetura dis sistema
$ arch

## Saber se tem vmx

#cat /proc/cpuinfo | grep vmx

## Registrar (Importante para poder utilizar os repositórios. Sem ele os repositórios não funcionam)

#subscription-manager register
#subscription-manager attach

## Instalar virtualização.

### Pesquisar Grupos

#dnf groulist

updating Subscription Management repositories.
Última verificação de data de vencimento de metadados: 1:51:50 atrás em sáb 17 abr 2021 15:16:43 -03.
Grupos de Ambientes Disponíveis:
   Server
   Instalações Mínimas
   Workstation
   Sistema Operacional Personalizado
   Máquina de Virtualização
Grupos de Ambientes Instalados:
   Servidor com GUI
Grupos instalados:
   Gestão de Contentores
   Gestão sem Cabeça
Grupos disponíveis:
   Compatibilidade da Legacia UNIX.
   Ferramentas de Desenvolvimento RPM
   Suporte a Smart Card
   Desenvolvimento do núcleo .net
   Servidores de Rede
   Ferramentas de Segurança
   Ferramentas de Desenvolvimento
   Suporte Científico
   Ferramentas do Sistema
   Ferramentas Administrativas gráficas

### Instalar grupo Virtualização
#dnf groupinstall -y "Virtualization Host"

#dnf groupinstall -y "Virtualization Client"

#systemctl status libvirtd

### Iniciar com a inicialização.

#systemctl enable libvirtd

## Acessar com ssh e acessar virtmanager

#ssh -X -lroot ip.da.maquina
 
 '-X ' -> permite visualizar aplicações gráficas remotamente.


## Acessar a estação e rodar o virtmanager 

#virt-manager &

<img src="virt-manager1.png">
<img src="virt-manager2.png">
<img src="virt-manager3.png">
<img src="virt-manager4.png">
<img src="virt-manager5.png">
<img src="virt-manager6.png">
<img src="virt-manager7.png">
<img src="virt-manager8.png">
<img src="virt-manager9.png">
<img src="virt-manager10.png">
<img src="virt-manager11.png">
