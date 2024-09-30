# Trebolinux 


## A grandes rasgos
Este repositorio responde a la necesidad de documentar el código (sea del tipo que sea)
para mi blog alojado en www.trebolinux.com 

## Componentes
* [Ansible](https://www.ansible.com)
* [Libvirt](https://libvirt.org/)
* [Vagrant](https://www.vagrantup.com/) 
* [Vagrant-libvirt](https://github.com/vagrant-libvirt/vagrant-libvirt)

## Ápéndices

### Desarrollo
Tanto instalación como mantenimiento serán íntegramente (hasta donde sea posible) realizadas
mediante [Ansible](https://www.ansible.com/).

Cada feature, despliegue o bugfix está probado on-prem usando [Vagrant](https://www.vagrantup.com/)
para mantener la portabilidad en la medida de lo posible sin sacrificar redundancia del entorno productivo
en entornos previos.

### Convenciones
#### Backlog
Para evitar gestión de backlog de forma farragosa utilizaré un estándar propio
donde la deuda técnica forma parte del código y puede ser procesado a posteriori
con el comando ```grep -Rns TODO *``` para obtener un archivo parseable de forma sencilla.

### Bibliografía
* [Ansible](https://docs.ansible.com/)
* [Vagrant](https://www.vagrantup.com/) 
* [Libvirt](https://libvirt.org/)
* [Vagrant-libvirt](https://vagrant-libvirt.github.io/vagrant-libvirt/)



