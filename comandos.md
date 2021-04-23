
## Saber arquitetura i sistema
$ arch

## Saber se tem vmx

#cat /proc/cpuinfo | grep vmx

## Registrar (Importante para poder utilizar os repositórios. Sem ele os repositórios não funcionam)

#subscription-manager register

#subscription-manager attach

## Instalar virtualização.

### Pesquisar Grupos

#dnf groulist

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
